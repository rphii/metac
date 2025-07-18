project('metac', 'c')

headers = [
  'attr.h',
  'colorprint.h',
  'endian-detect.h',
  'err.h',
  'platform-detect.h',
  ]

install_headers(headers, subdir: 'rphii')

pkg = import('pkgconfig')
pkg.generate(
  version: '1.0',
  name: 'metac',
  description: 'Essential C headers.',
  )



