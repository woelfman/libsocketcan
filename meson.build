project('libsocketcan', 'c')

libsocketcan_src = [
  'src/libsocketcan.c',
]

libsocketcan_inc = include_directories('include')

libsocketcan = library('socketcan', [libsocketcan_src],
  include_directories : libsocketcan_inc)

libsocketcan_dep = declare_dependency(
  link_with : [libsocketcan],
  include_directories : ['include'])
