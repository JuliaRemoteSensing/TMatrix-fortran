project('tmatrix', 'fortran', meson_version: '>=0.53', license: 'MIT')

add_project_arguments('-funroll-all-loops', language: 'fortran')
add_project_arguments('-fno-f2c', language: 'fortran')

shared_library('tmatrixfo', files('ampld.lp.f', 'lpd.f'), install : true, install_dir: '/workspace/destdir/lib')
shared_library('tmatrixro', files('tmd.lp.f', 'lpd.f'), install : true, install_dir: '/workspace/destdir/lib')
install_data('LICENSE', install_dir: '/workspace/destdir/shared/licenses')
