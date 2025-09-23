CC 				= cc
CFLAGS 		= -Wall -g

BUILD_DIR = build
SRCS 			= $(wildcard *.c)
TARGET 		= $(BUILD_DIR)/ex25

$(TARGET): $(SRCS)
			@mkdir -p $(BUILD_DIR)
			$(CC) $(CFLAGS) $^ -o $@

clean:
			rm -rf $(BUILD_DIR)
