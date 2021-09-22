# Our binary is produced here
bin_PROGRAMS = c_cpp_project
c_cpp_project_SOURCES = c_cpp_project.cpp
# main binary will be installed into the default directory for "bin"s (hence we used the bin
# prefix
noinst_LIBRARIES = libhelper.a
libhelper_a_SOURCES = helper.cpp
# noinst_ : assures that this library is not installed to the user's computer
# libBLAH.a is a Unix convention. If you noticed, we replaced the . with _ in SOURCES line.
c_cpp_project_LDADD = libhelper.a ../my_inc/libmyadd.a
# LDADD specifies which libraries to compile into "c_cpp_project". We have two libraries.
# libhelper comes from this directory and libmyadd come from my_inc directory.
