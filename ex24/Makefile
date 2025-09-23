CC = cc
CFLAGS = -Wall -g -DNDEBUG

SRCS = $(wildcard *.c)
BUILD_DIR = build
TARGET = $(BUILD_DIR)/ex24

$(TARGET): $(SRCS)
			@mkdir -p $(BUILD_DIR)
			$(CC) $(CFLAGS) $^ -o $@

clean:
		rm -rf $(BUILD_DIR)
