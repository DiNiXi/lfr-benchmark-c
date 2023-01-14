project('c++ lfr', 'cpp',
        version : '1.0.0',
        default_options: ['buildtype=release'] )

subdir('symm-unwgt-sources')
subdir('symm-wgt-sources')
subdir('nonsymm-unwgt-sources')
subdir('nonsymm-wgt-sources')

pkg_mod = import('pkgconfig')
pkg_mod.generate(libraries : liblfrsymmunwgt,
                 version : '1.0',
                 name : 'lfrsymmunwgt',
                 description : 'Symmetric, unweighted benchmark graphs.')

pkg_mod.generate(libraries : liblfrsymmwgt,
                 version : '1.0',
                 name : 'lfrsymmwgt',
                 description : 'Symmetric, weighted benchmark graphs.')

pkg_mod.generate(libraries : liblfrnonsymmunwgt,
                 version : '1.0',
                 name : 'lfrnonsymmunwgt',
                 description : 'Non-symmetric, unweighted benchmark graphs.')

pkg_mod.generate(libraries : liblfrnonsymmwgt,
                 version : '1.0',
                 name : 'lfrnonsymmwgt',
                 description : 'Non-symmetric, weighted benchmark graphs.')
