AUTOMAKE_OPTIONS=foreign no-dependencies

noinst_LIBRARIES = libfile_api.a

libfile_api_a_SOURCES = \
file_api.h \
file_service.cc file_service.h \
file_service_config.cc file_service_config.h \
file_mime_process.h file_mime_process.cc \
file_resume_block.cc file_resume_block.h \
file_mime_config.cc file_mime_config.h \
file_capture.cc file_capture.h \
circular_buffer.cc circular_buffer.h \
file_mempool.cc file_mempool.h \
file_stats.cc file_stats.h
 
AM_CXXFLAGS = @AM_CXXFLAGS@

SUBDIRS = libs
