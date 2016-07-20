# gnuplot_c_interface_linux
A version of gnuplot interface for c/c++ in linux

THIS IS NOT MY CODE, I JUST USE AND MODIFICATE FOR IMPROVE SAME PROBLEMS ON MY APLICATION

Reference to original code gnuplot_i.hpp

////////////////////////////////////////////////////////////////////////////////
///
///  \brief A C++ interface to gnuplot.
///
///
///  The interface uses pipes and so won't run on a system that doesn't have
///  POSIX pipe support Tested on Windows (MinGW and Visual C++) and Linux (GCC)
///
/// Version history:
/// 0. C interface
///    by N. Devillard (27/01/03)
/// 1. C++ interface: direct translation from the C interface
///    by Rajarshi Guha (07/03/03)
/// 2. corrections for Win32 compatibility
///    by V. Chyzhdzenka (20/05/03)
/// 3. some member functions added, corrections for Win32 and Linux
///    compatibility
///    by M. Burgis (10/03/08)
///
/// Requirements:
/// * gnuplot has to be installed (http://www.gnuplot.info/download.html)
/// * for Windows: set Path-Variable for Gnuplot path
///         (e.g. C:/program files/gnuplot/bin)
///         or set Gnuplot path with:
///         Gnuplot::set_GNUPlotPath(const std::string &path);
///
////////////////////////////////////////////////////////////////////////////////
