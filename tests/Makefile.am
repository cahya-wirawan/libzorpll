AM_CPPFLAGS=-I$(top_srcdir)/src -I../src -DSRCDIR=\"$(top_srcdir)/tests\" -DBOOST_TEST_DYN_LINK=1

check_PROGRAMS = test_zcrypt test_readline test_registry test_conns test_ssl test_streams test_random test_valid_chars test_sockaddr test_blob test_base64 test_codegzip test_codecipher test_portrandom test_pktbuf

LDADD = -lboost_unit_test_framework ../src/libzorpll.la -lm

test_zcrypt_SOURCES = test_zcrypt.cc

test_readline_SOURCES = test_readline.cc

test_registry_SOURCES = test_registry.cc

test_conns_SOURCES = test_conns.cc

test_ssl_SOURCES = test_ssl.cc

test_random_SOURCES = test_random.cc

test_streams_SOURCES = test_streams.cc

test_valid_chars_SOURCES = test_valid_chars.cc

test_sockaddr_SOURCES = test_sockaddr.cc

test_blob_SOURCES = test_blob.cc

test_base64_SOURCES = test_base64.cc

test_codegzip_SOURCES = test_codegzip.cc

test_codecipher_SOURCES = test_codecipher.cc

test_portrandom_SOURCES = test_portrandom.cc randtest.cc randtest.h

test_pktbuf_SOURCES = test_pktbuf.cc

TESTS = test_registry test_readline test_zcrypt test_conns test_ssl test_random test_streams test_valid_chars test_sockaddr test_blob test_base64 test_codegzip test_codecipher test_portrandom test_pktbuf
