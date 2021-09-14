project('tmatrix', 'fortran', meson_version: '>=0.53', license: 'MIT')

lib_dir = '/workspace/destdir/lib'
if host_machine.system() in ['windows']
  lib_dir = '/workspace/destdir/bin'
endif

add_project_arguments('-O3', language: 'fortran')
add_project_arguments('-funroll-all-loops', language: 'fortran')
add_project_arguments('-fno-f2c', language: 'fortran')

shared_library('tmatrixfo', files('ampld.lp.f', 'lpd.f'), install : true, install_dir: lib_dir)
shared_library('tmatrixro', files('tmd.lp.f', 'lpd.f'), install : true, install_dir: lib_dir)
install_data('LICENSE', install_dir: '/workspace/destdir/shared/licenses')
