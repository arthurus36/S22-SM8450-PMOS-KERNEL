obj-$(CONFIG_SEC_KUNIT)		+= test.o mock.o common-mocks.o strerror.o \
  string-stream.o test-stream.o test-executor.o try-catch.o
obj-$(CONFIG_SEC_KUNIT_TEST)		+= \
  test-mock.o mock-macro-test.o mock-test.o strerror-test.o \
  string-stream-test.o test-stream-test.o test-test.o
obj-$(CONFIG_SEC_KUNIT_DEATH_TEST)	+= test-death-test.o
obj-$(CONFIG_SEC_EXAMPLE_TEST)	+= example-test.o

GCOV_PROFILE := $(CONFIG_SEC_KUNIT)
