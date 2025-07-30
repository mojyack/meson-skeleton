project('app', 'cpp', version : '1.0.0', default_options : ['warning_level=3', 'werror=false', 'cpp_std=c++23'])
add_project_arguments('-Wfatal-errors', language: 'cpp')
add_project_arguments('-Wno-missing-field-initializers', language: 'cpp')

deps = [
  dependency('some-dep', version : ['>=1.0', '<2.0']),
]

executable('app',
  files(
    'src/main.cpp',
  ), 
  dependencies : deps,
  install : true,
)
