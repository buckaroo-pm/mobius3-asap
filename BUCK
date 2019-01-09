load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'asap',
  header_namespace = '',
  header_only = True,
  exported_headers = subdir_glob([
    ('include/asap', '**/*.h'),
    ('include/asap', '**/*.tcc'),
  ]),
  licenses = [
    'COPYING',
  ],
  visibility = [
    'PUBLIC',
  ],
)
