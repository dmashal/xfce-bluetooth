

libexec_PROGRAMS = xfce-bluetooth xfce-bluetooth-agent
xfce_bluetooth_SOURCES = xfce-bluetooth.vala BluezInterface.vala
xfce_bluetooth_CFLAGS = @GLIB_CFLAGS@ \
	@GIO_CFLAGS@ \
	@GMODULE_CFLAGS@ \
	@LIBXFCE4UI_CFLAGS@
xfce_bluetooth_LDADD = @GLIB_LIBS@ \
	@GIO_LIBS@ \
	@GMODULE_LIBS@ \
	@LIBXFCE4UI_LIBS@

xfce_bluetooth_agent_SOURCES = xfce-bluetooth-agent.vala BluezInterface.vala
xfce_bluetooth_agent_CFLAGS = @GLIB_CFLAGS@ \
	@GIO_CFLAGS@ \
	@GMODULE_CFLAGS@ \
	@LIBXFCE4UI_CFLAGS@
xfce_bluetooth_agent_LDADD = @GLIB_LIBS@ \
	@GIO_LIBS@ \
	@GMODULE_LIBS@ \
	@LIBXFCE4UI_LIBS@

AM_VALAFLAGS = --pkg gtk+-2.0 --pkg gmodule-2.0 --pkg gio-2.0 --pkg libxfce4ui-1
