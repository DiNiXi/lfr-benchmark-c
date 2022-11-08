project('c++ lfr binary', 'cpp',
        version : '1.0.0',
        default_options: ['buildtype=release'] )

subdir('Sources')

pkg_mod = import('pkgconfig')
pkg_mod.generate(libraries : lfrbinlib,
                 version : '1.0',
                 name : 'liblfrbin',
                 filebase : 'lfr',
                 description : 'A C++ library for Leiden.')
