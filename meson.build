project('watts-up', 'c')

libsrc=[
  'util.c',
  'config.c',
  'globals.c',
]

src=[
  'wattsup.c',
]

lib = library('wattsup', libsrc)

executable('wattsup', src, link_with: lib, install: true)
