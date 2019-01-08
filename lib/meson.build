lib_sources = [
	'convert.cpp',
	'debug.cpp',
	'error.cpp',
	'input.cpp',
	'matcher.cpp',
	'pattern.cpp',
	'posix.cpp',
	'unicode.cpp',
	'utf8.cpp',
	'../unicode/block_scripts.cpp',
	'../unicode/language_scripts.cpp',
	'../unicode/letter_scripts.cpp',
]

libreflex = library('reflex', lib_sources,
	include_directories: inc)
libreflex_dep = declare_dependency(
	link_with: libreflex,
	include_directories: inc_sys)
