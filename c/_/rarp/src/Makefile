# 6Harmonics Inc.
# by Qige: qige@6harmonics.com, qige.zhao@6wilink.com, 2016.06.29

APP=rarp

all: $(APP)

$(APP): *.c
	$(CC) $(CFLAGS) $(EXTRA_CFLAGS) -I. -o $@ $^ -L.

clean:
	rm -f $(APP)

