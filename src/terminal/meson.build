if conf_data.get('CONFIG_KITTY')
	srcs += files('kitty.c', 'map.cpp')
endif
if conf_data.get('CONFIG_MOUSE')
	srcs += files('mouse.c')
endif
if conf_data.get('CONFIG_LIBSIXEL')
	srcs += files('sixel.c')
endif
if conf_data.get('CONFIG_TERMINFO')
	srcs += files('terminfo.c')
endif
srcs += files('color.c', 'draw.c', 'event.c', 'hardio.c', 'image.c', 'kbd.c', 'screen.c', 'tab.c', 'terminal.c', 'window.c')
