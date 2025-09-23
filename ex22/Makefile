CC = cc
CFLAGS = -Wall -g -o2 -DNDEBUG

BUILD_DIR = build
SRCS 			= $(wildcard *.c)
TARGETS		= $(BUILD_DIR)/ex22-main

$(TARGETS): $(SRCS)
		@mkdir -p $(BUILD_DIR)
		$(CC) $(CFLAGS) $^ -o $@

clean:
	rm -rf $(BUILD_DIR)


