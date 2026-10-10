# SPDX-License-Identifier: BSD-3-Clause

project ('helloworld', 'c',
	version: files('VERSION'),
	license: 'BSD',
	default_options: [
		'buildtype=release',
		'c_std=c11',
		'default_library=static',
		'warning_level=2',
	],
	meson_version: '>=0.57'
)

source_root = meson.current_source_dir()
build_root = meson.current_build_dir()

subdir('src')

message('build config complete:\n' +
    ' source path ="' + source_root + '"\n' +
    ' build path = "' + build_root + '"')
