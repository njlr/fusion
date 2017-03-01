include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-fusion',
  header_only = True,
  header_namespace = 'boost/fusion',
  exported_headers = subdir_glob([
    ('include/boost/fusion', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
