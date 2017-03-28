include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'uuid',
  header_only = True,
  header_namespace = 'include/boost/uuid',
  exported_headers = subdir_glob([
    ('include/boost/uuid', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
