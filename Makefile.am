AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -Wextra -O2 $(NLINC) -DCONFIG_LIBNL32
LDFLAGS = -lnl-3 -lnl-genl-3 -lm

bin_PROGRAMS = calibrator

calibrator_SOURCES = \
	nvs.c misc_cmds.c calibrator.c plt.c wl18xx_plt.c ini.c
