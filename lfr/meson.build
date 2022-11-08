project('c++ lfr binary', 'cpp',
        version : '1.0.0',
        default_options: ['buildtype=release'] )

subdir('Sources')

pkg_mod = import('pkgconfig')
pkg_mod.generate(libraries : liblfrbenchmark,
                 version : '1.0',
                 name : 'liblfrbenchmark',
                 filebase : 'lfr',
                 description : 'A C++ library for Leiden.')
