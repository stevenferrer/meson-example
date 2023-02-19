project('mesonexample', 'cpp', version: '0.1.0', default_options : ['cpp_std=c++17'])

catch2_dep = dependency('catch2-with-main')
boost_dep = dependency('boost')

example_test = executable('example-test', ['example_test.cpp'], dependencies: [catch2_dep])
test('example test', example_test)

main_exe = executable('mesonexample', ['main.cpp'])