

SET(OFX_TEST_INCLUDE_DIRS
  ${LIBOFX_INCLUDE_DIRS}
)
SET(OFX_TEST_LIBS)

GNC_ADD_TEST(test-link-ofx test-link.c OFX_TEST_INCLUDE_DIRS OFX_TEST_LIBS)