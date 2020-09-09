Compilation and installation on MacOSX.
NOTE: install in /usr/local/lib is hard-coded.
Check lpsolve55/ccc.osx to change install_name if needed.

cd lpsolve55
sh ccc.osx
cd bin/osx64
sudo install libplsolve55.a liblpsolve55.dylib /usr/local/lib
cd ../../..
sudo install -m 664 lp_lib.h lp_types.h lp_utils.h lp_matrix.h lp_mipbb.h lp_Hash.h lp_SOS.h /usr/local/include
