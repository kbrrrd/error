In file included from /usr/include/google/protobuf/stubs/common.h:21,
                 from /usr/include/google/protobuf/io/coded_stream.h:108,
                 from /home/kbrd/libopenshot/build/src/objdetectdata.pb.h:20,
                 from /home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:6:
/usr/include/absl/strings/string_view.h:53:26: 错误：‘string_view’不是命名空间‘std’中的一个类型名
   53 | using string_view = std::string_view;
      |                          ^~~~~~~~~~~
/usr/include/absl/strings/string_view.h:53:21: 附注：‘std::string_view’ is only available from C++17 onwards
   53 | using string_view = std::string_view;
      |                     ^~~
/usr/include/absl/strings/string_view.h:752:8: 错误：‘string_view’不是一个类型名
  752 | inline string_view ClippedSubstr(string_view s, size_t pos,
      |        ^~~~~~~~~~~
/usr/include/absl/strings/string_view.h:763:11: 错误：‘string_view’不是一个类型名
  763 | constexpr string_view NullSafeStringView(absl::Nullable<const char*> p) {
      |           ^~~~~~~~~~~
In file included from /usr/include/absl/log/internal/check_op.h:38,
                 from /usr/include/absl/log/internal/check_impl.h:19,
                 from /usr/include/absl/log/absl_check.h:38,
                 from /usr/include/google/protobuf/io/coded_stream.h:110:
/usr/include/absl/log/internal/nullstream.h:49:32: 错误：‘absl::string_view’尚未声明
   49 |   NullStream& AtLocation(absl::string_view, int) { return *this; }
      |                                ^~~~~~~~~~~
In file included from /usr/include/absl/time/time.h:97,
                 from /usr/include/absl/log/log_entry.h:35,
                 from /usr/include/absl/log/internal/log_message.h:41,
                 from /usr/include/absl/log/internal/strip.h:25,
                 from /usr/include/absl/log/internal/check_op.h:39:
/usr/include/absl/time/civil_time.h:515:27: 错误：‘string_view’不是‘absl’的成员
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |                           ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:515:53: 错误：expected primary-expression before ‘*’ token
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |                                                     ^
/usr/include/absl/time/civil_time.h:515:55: 错误：‘c’在此作用域中尚未声明
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |                                                       ^
/usr/include/absl/time/civil_time.h:515:56: 错误：expression list treated as compound expression in initializer [-fpermissive]
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |                                                        ^
/usr/include/absl/time/civil_time.h:516:6: 错误：‘bool absl::lts_20240722::ParseCivilTime’ 重定义
  516 | bool ParseCivilTime(absl::string_view s, CivilMinute* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:515:6: 附注：‘bool absl::lts_20240722::ParseCivilTime’ previously defined here
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:516:27: 错误：‘string_view’不是‘absl’的成员
  516 | bool ParseCivilTime(absl::string_view s, CivilMinute* c);
      |                           ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:516:53: 错误：expected primary-expression before ‘*’ token
  516 | bool ParseCivilTime(absl::string_view s, CivilMinute* c);
      |                                                     ^
/usr/include/absl/time/civil_time.h:516:55: 错误：‘c’在此作用域中尚未声明
  516 | bool ParseCivilTime(absl::string_view s, CivilMinute* c);
      |                                                       ^
/usr/include/absl/time/civil_time.h:517:6: 错误：‘bool absl::lts_20240722::ParseCivilTime’ 重定义
  517 | bool ParseCivilTime(absl::string_view s, CivilHour* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:515:6: 附注：‘bool absl::lts_20240722::ParseCivilTime’ previously defined here
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:517:27: 错误：‘string_view’不是‘absl’的成员
  517 | bool ParseCivilTime(absl::string_view s, CivilHour* c);
      |                           ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:517:51: 错误：expected primary-expression before ‘*’ token
  517 | bool ParseCivilTime(absl::string_view s, CivilHour* c);
      |                                                   ^
/usr/include/absl/time/civil_time.h:517:53: 错误：‘c’在此作用域中尚未声明
  517 | bool ParseCivilTime(absl::string_view s, CivilHour* c);
      |                                                     ^
/usr/include/absl/time/civil_time.h:518:6: 错误：‘bool absl::lts_20240722::ParseCivilTime’ 重定义
  518 | bool ParseCivilTime(absl::string_view s, CivilDay* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:515:6: 附注：‘bool absl::lts_20240722::ParseCivilTime’ previously defined here
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:518:27: 错误：‘string_view’不是‘absl’的成员
  518 | bool ParseCivilTime(absl::string_view s, CivilDay* c);
      |                           ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:518:50: 错误：expected primary-expression before ‘*’ token
  518 | bool ParseCivilTime(absl::string_view s, CivilDay* c);
      |                                                  ^
/usr/include/absl/time/civil_time.h:518:52: 错误：‘c’在此作用域中尚未声明
  518 | bool ParseCivilTime(absl::string_view s, CivilDay* c);
      |                                                    ^
/usr/include/absl/time/civil_time.h:519:6: 错误：‘bool absl::lts_20240722::ParseCivilTime’ 重定义
  519 | bool ParseCivilTime(absl::string_view s, CivilMonth* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:515:6: 附注：‘bool absl::lts_20240722::ParseCivilTime’ previously defined here
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:519:27: 错误：‘string_view’不是‘absl’的成员
  519 | bool ParseCivilTime(absl::string_view s, CivilMonth* c);
      |                           ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:519:52: 错误：expected primary-expression before ‘*’ token
  519 | bool ParseCivilTime(absl::string_view s, CivilMonth* c);
      |                                                    ^
/usr/include/absl/time/civil_time.h:519:54: 错误：‘c’在此作用域中尚未声明
  519 | bool ParseCivilTime(absl::string_view s, CivilMonth* c);
      |                                                      ^
/usr/include/absl/time/civil_time.h:520:6: 错误：‘bool absl::lts_20240722::ParseCivilTime’ 重定义
  520 | bool ParseCivilTime(absl::string_view s, CivilYear* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:515:6: 附注：‘bool absl::lts_20240722::ParseCivilTime’ previously defined here
  515 | bool ParseCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:520:27: 错误：‘string_view’不是‘absl’的成员
  520 | bool ParseCivilTime(absl::string_view s, CivilYear* c);
      |                           ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:520:51: 错误：expected primary-expression before ‘*’ token
  520 | bool ParseCivilTime(absl::string_view s, CivilYear* c);
      |                                                   ^
/usr/include/absl/time/civil_time.h:520:53: 错误：‘c’在此作用域中尚未声明
  520 | bool ParseCivilTime(absl::string_view s, CivilYear* c);
      |                                                     ^
/usr/include/absl/time/civil_time.h:535:34: 错误：‘string_view’不是‘absl’的成员
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |                                  ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:535:60: 错误：expected primary-expression before ‘*’ token
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |                                                            ^
/usr/include/absl/time/civil_time.h:535:62: 错误：‘c’在此作用域中尚未声明
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |                                                              ^
/usr/include/absl/time/civil_time.h:535:63: 错误：expression list treated as compound expression in initializer [-fpermissive]
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |                                                               ^
/usr/include/absl/time/civil_time.h:536:6: 错误：‘bool absl::lts_20240722::ParseLenientCivilTime’ 重定义
  536 | bool ParseLenientCivilTime(absl::string_view s, CivilMinute* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:535:6: 附注：‘bool absl::lts_20240722::ParseLenientCivilTime’ previously defined here
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:536:34: 错误：‘string_view’不是‘absl’的成员
  536 | bool ParseLenientCivilTime(absl::string_view s, CivilMinute* c);
      |                                  ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:536:60: 错误：expected primary-expression before ‘*’ token
  536 | bool ParseLenientCivilTime(absl::string_view s, CivilMinute* c);
      |                                                            ^
/usr/include/absl/time/civil_time.h:536:62: 错误：‘c’在此作用域中尚未声明
  536 | bool ParseLenientCivilTime(absl::string_view s, CivilMinute* c);
      |                                                              ^
/usr/include/absl/time/civil_time.h:537:6: 错误：‘bool absl::lts_20240722::ParseLenientCivilTime’ 重定义
  537 | bool ParseLenientCivilTime(absl::string_view s, CivilHour* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:535:6: 附注：‘bool absl::lts_20240722::ParseLenientCivilTime’ previously defined here
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:537:34: 错误：‘string_view’不是‘absl’的成员
  537 | bool ParseLenientCivilTime(absl::string_view s, CivilHour* c);
      |                                  ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:537:58: 错误：expected primary-expression before ‘*’ token
  537 | bool ParseLenientCivilTime(absl::string_view s, CivilHour* c);
      |                                                          ^
/usr/include/absl/time/civil_time.h:537:60: 错误：‘c’在此作用域中尚未声明
  537 | bool ParseLenientCivilTime(absl::string_view s, CivilHour* c);
      |                                                            ^
/usr/include/absl/time/civil_time.h:538:6: 错误：‘bool absl::lts_20240722::ParseLenientCivilTime’ 重定义
  538 | bool ParseLenientCivilTime(absl::string_view s, CivilDay* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:535:6: 附注：‘bool absl::lts_20240722::ParseLenientCivilTime’ previously defined here
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:538:34: 错误：‘string_view’不是‘absl’的成员
  538 | bool ParseLenientCivilTime(absl::string_view s, CivilDay* c);
      |                                  ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:538:57: 错误：expected primary-expression before ‘*’ token
  538 | bool ParseLenientCivilTime(absl::string_view s, CivilDay* c);
      |                                                         ^
/usr/include/absl/time/civil_time.h:538:59: 错误：‘c’在此作用域中尚未声明
  538 | bool ParseLenientCivilTime(absl::string_view s, CivilDay* c);
      |                                                           ^
/usr/include/absl/time/civil_time.h:539:6: 错误：‘bool absl::lts_20240722::ParseLenientCivilTime’ 重定义
  539 | bool ParseLenientCivilTime(absl::string_view s, CivilMonth* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:535:6: 附注：‘bool absl::lts_20240722::ParseLenientCivilTime’ previously defined here
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:539:34: 错误：‘string_view’不是‘absl’的成员
  539 | bool ParseLenientCivilTime(absl::string_view s, CivilMonth* c);
      |                                  ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:539:59: 错误：expected primary-expression before ‘*’ token
  539 | bool ParseLenientCivilTime(absl::string_view s, CivilMonth* c);
      |                                                           ^
/usr/include/absl/time/civil_time.h:539:61: 错误：‘c’在此作用域中尚未声明
  539 | bool ParseLenientCivilTime(absl::string_view s, CivilMonth* c);
      |                                                             ^
/usr/include/absl/time/civil_time.h:540:6: 错误：‘bool absl::lts_20240722::ParseLenientCivilTime’ 重定义
  540 | bool ParseLenientCivilTime(absl::string_view s, CivilYear* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:535:6: 附注：‘bool absl::lts_20240722::ParseLenientCivilTime’ previously defined here
  535 | bool ParseLenientCivilTime(absl::string_view s, CivilSecond* c);
      |      ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:540:34: 错误：‘string_view’不是‘absl’的成员
  540 | bool ParseLenientCivilTime(absl::string_view s, CivilYear* c);
      |                                  ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:540:58: 错误：expected primary-expression before ‘*’ token
  540 | bool ParseLenientCivilTime(absl::string_view s, CivilYear* c);
      |                                                          ^
/usr/include/absl/time/civil_time.h:540:60: 错误：‘c’在此作用域中尚未声明
  540 | bool ParseLenientCivilTime(absl::string_view s, CivilYear* c);
      |                                                            ^
/usr/include/absl/time/civil_time.h:566:26: 错误：‘string_view’不是‘absl’的成员
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:566:52: 错误：expected primary-expression before ‘*’ token
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |                                                    ^
/usr/include/absl/time/civil_time.h:566:54: 错误：‘c’在此作用域中尚未声明
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |                                                      ^
/usr/include/absl/time/civil_time.h:566:68: 错误：expected primary-expression before ‘*’ token
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |                                                                    ^
/usr/include/absl/time/civil_time.h:566:70: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |                                                                      ^~~~~
      |                                                                      perror
/usr/include/absl/time/civil_time.h:566:75: 错误：expression list treated as compound expression in initializer [-fpermissive]
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |                                                                           ^
/usr/include/absl/time/civil_time.h:567:6: 错误：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ 重定义
  567 | bool AbslParseFlag(absl::string_view s, CivilMinute* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:566:6: 附注：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ previously defined here
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:567:26: 错误：‘string_view’不是‘absl’的成员
  567 | bool AbslParseFlag(absl::string_view s, CivilMinute* c, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:567:52: 错误：expected primary-expression before ‘*’ token
  567 | bool AbslParseFlag(absl::string_view s, CivilMinute* c, std::string* error);
      |                                                    ^
/usr/include/absl/time/civil_time.h:567:54: 错误：‘c’在此作用域中尚未声明
  567 | bool AbslParseFlag(absl::string_view s, CivilMinute* c, std::string* error);
      |                                                      ^
/usr/include/absl/time/civil_time.h:567:68: 错误：expected primary-expression before ‘*’ token
  567 | bool AbslParseFlag(absl::string_view s, CivilMinute* c, std::string* error);
      |                                                                    ^
/usr/include/absl/time/civil_time.h:567:70: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
  567 | bool AbslParseFlag(absl::string_view s, CivilMinute* c, std::string* error);
      |                                                                      ^~~~~
      |                                                                      perror
/usr/include/absl/time/civil_time.h:568:6: 错误：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ 重定义
  568 | bool AbslParseFlag(absl::string_view s, CivilHour* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:566:6: 附注：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ previously defined here
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:568:26: 错误：‘string_view’不是‘absl’的成员
  568 | bool AbslParseFlag(absl::string_view s, CivilHour* c, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:568:50: 错误：expected primary-expression before ‘*’ token
  568 | bool AbslParseFlag(absl::string_view s, CivilHour* c, std::string* error);
      |                                                  ^
/usr/include/absl/time/civil_time.h:568:52: 错误：‘c’在此作用域中尚未声明
  568 | bool AbslParseFlag(absl::string_view s, CivilHour* c, std::string* error);
      |                                                    ^
/usr/include/absl/time/civil_time.h:568:66: 错误：expected primary-expression before ‘*’ token
  568 | bool AbslParseFlag(absl::string_view s, CivilHour* c, std::string* error);
      |                                                                  ^
/usr/include/absl/time/civil_time.h:568:68: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
  568 | bool AbslParseFlag(absl::string_view s, CivilHour* c, std::string* error);
      |                                                                    ^~~~~
      |                                                                    perror
/usr/include/absl/time/civil_time.h:569:6: 错误：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ 重定义
  569 | bool AbslParseFlag(absl::string_view s, CivilDay* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:566:6: 附注：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ previously defined here
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:569:26: 错误：‘string_view’不是‘absl’的成员
  569 | bool AbslParseFlag(absl::string_view s, CivilDay* c, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:569:49: 错误：expected primary-expression before ‘*’ token
  569 | bool AbslParseFlag(absl::string_view s, CivilDay* c, std::string* error);
      |                                                 ^
/usr/include/absl/time/civil_time.h:569:51: 错误：‘c’在此作用域中尚未声明
  569 | bool AbslParseFlag(absl::string_view s, CivilDay* c, std::string* error);
      |                                                   ^
/usr/include/absl/time/civil_time.h:569:65: 错误：expected primary-expression before ‘*’ token
  569 | bool AbslParseFlag(absl::string_view s, CivilDay* c, std::string* error);
      |                                                                 ^
/usr/include/absl/time/civil_time.h:569:67: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
  569 | bool AbslParseFlag(absl::string_view s, CivilDay* c, std::string* error);
      |                                                                   ^~~~~
      |                                                                   perror
/usr/include/absl/time/civil_time.h:570:6: 错误：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ 重定义
  570 | bool AbslParseFlag(absl::string_view s, CivilMonth* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:566:6: 附注：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ previously defined here
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:570:26: 错误：‘string_view’不是‘absl’的成员
  570 | bool AbslParseFlag(absl::string_view s, CivilMonth* c, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:570:51: 错误：expected primary-expression before ‘*’ token
  570 | bool AbslParseFlag(absl::string_view s, CivilMonth* c, std::string* error);
      |                                                   ^
/usr/include/absl/time/civil_time.h:570:53: 错误：‘c’在此作用域中尚未声明
  570 | bool AbslParseFlag(absl::string_view s, CivilMonth* c, std::string* error);
      |                                                     ^
/usr/include/absl/time/civil_time.h:570:67: 错误：expected primary-expression before ‘*’ token
  570 | bool AbslParseFlag(absl::string_view s, CivilMonth* c, std::string* error);
      |                                                                   ^
/usr/include/absl/time/civil_time.h:570:69: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
  570 | bool AbslParseFlag(absl::string_view s, CivilMonth* c, std::string* error);
      |                                                                     ^~~~~
      |                                                                     perror
/usr/include/absl/time/civil_time.h:571:6: 错误：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ 重定义
  571 | bool AbslParseFlag(absl::string_view s, CivilYear* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:566:6: 附注：‘bool absl::lts_20240722::time_internal::AbslParseFlag’ previously defined here
  566 | bool AbslParseFlag(absl::string_view s, CivilSecond* c, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/civil_time.h:571:26: 错误：‘string_view’不是‘absl’的成员
  571 | bool AbslParseFlag(absl::string_view s, CivilYear* c, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/civil_time.h:571:50: 错误：expected primary-expression before ‘*’ token
  571 | bool AbslParseFlag(absl::string_view s, CivilYear* c, std::string* error);
      |                                                  ^
/usr/include/absl/time/civil_time.h:571:52: 错误：‘c’在此作用域中尚未声明
  571 | bool AbslParseFlag(absl::string_view s, CivilYear* c, std::string* error);
      |                                                    ^
/usr/include/absl/time/civil_time.h:571:66: 错误：expected primary-expression before ‘*’ token
  571 | bool AbslParseFlag(absl::string_view s, CivilYear* c, std::string* error);
      |                                                                  ^
/usr/include/absl/time/civil_time.h:571:68: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
  571 | bool AbslParseFlag(absl::string_view s, CivilYear* c, std::string* error);
      |                                                                    ^~~~~
      |                                                                    perror
/usr/include/absl/time/time.h:714:26: 错误：‘string_view’不是‘absl’的成员
  714 | bool ParseDuration(absl::string_view dur_string, Duration* d);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/time.h:714:58: 错误：expected primary-expression before ‘*’ token
  714 | bool ParseDuration(absl::string_view dur_string, Duration* d);
      |                                                          ^
/usr/include/absl/time/time.h:714:60: 错误：‘d’在此作用域中尚未声明
  714 | bool ParseDuration(absl::string_view dur_string, Duration* d);
      |                                                            ^
/usr/include/absl/time/time.h:714:61: 错误：expression list treated as compound expression in initializer [-fpermissive]
  714 | bool ParseDuration(absl::string_view dur_string, Duration* d);
      |                                                             ^
/usr/include/absl/time/time.h:721:26: 错误：‘string_view’不是‘absl’的成员
  721 | bool AbslParseFlag(absl::string_view text, Duration* dst, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/time.h:721:52: 错误：expected primary-expression before ‘*’ token
  721 | bool AbslParseFlag(absl::string_view text, Duration* dst, std::string* error);
      |                                                    ^
/usr/include/absl/time/time.h:721:54: 错误：‘dst’在此作用域中尚未声明
  721 | bool AbslParseFlag(absl::string_view text, Duration* dst, std::string* error);
      |                                                      ^~~
/usr/include/absl/time/time.h:721:70: 错误：expected primary-expression before ‘*’ token
  721 | bool AbslParseFlag(absl::string_view text, Duration* dst, std::string* error);
      |                                                                      ^
/usr/include/absl/time/time.h:721:72: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
  721 | bool AbslParseFlag(absl::string_view text, Duration* dst, std::string* error);
      |                                                                        ^~~~~
      |                                                                        perror
/usr/include/absl/time/time.h:721:77: 错误：expression list treated as compound expression in initializer [-fpermissive]
  721 | bool AbslParseFlag(absl::string_view text, Duration* dst, std::string* error);
      |                                                                             ^
/usr/include/absl/time/time.h:1048:6: 错误：‘bool absl::lts_20240722::AbslParseFlag’ 重定义
 1048 | bool AbslParseFlag(absl::string_view text, Time* t, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/time.h:721:6: 附注：‘bool absl::lts_20240722::AbslParseFlag’ previously defined here
  721 | bool AbslParseFlag(absl::string_view text, Duration* dst, std::string* error);
      |      ^~~~~~~~~~~~~
/usr/include/absl/time/time.h:1048:26: 错误：‘string_view’不是‘absl’的成员
 1048 | bool AbslParseFlag(absl::string_view text, Time* t, std::string* error);
      |                          ^~~~~~~~~~~
/usr/include/absl/time/time.h:1048:48: 错误：expected primary-expression before ‘*’ token
 1048 | bool AbslParseFlag(absl::string_view text, Time* t, std::string* error);
      |                                                ^
/usr/include/absl/time/time.h:1048:50: 错误：‘t’ was not declared in this scope; did you mean ‘tm’?
 1048 | bool AbslParseFlag(absl::string_view text, Time* t, std::string* error);
      |                                                  ^
      |                                                  tm
/usr/include/absl/time/time.h:1048:64: 错误：expected primary-expression before ‘*’ token
 1048 | bool AbslParseFlag(absl::string_view text, Time* t, std::string* error);
      |                                                                ^
/usr/include/absl/time/time.h:1048:66: 错误：‘error’ was not declared in this scope; did you mean ‘perror’?
 1048 | bool AbslParseFlag(absl::string_view text, Time* t, std::string* error);
      |                                                                  ^~~~~
      |                                                                  perror
/usr/include/absl/time/time.h:1252:32: 错误：‘string_view’不是‘absl’的成员
 1252 | inline bool LoadTimeZone(absl::string_view name, TimeZone* tz) {
      |                                ^~~~~~~~~~~
/usr/include/absl/time/time.h:1252:58: 错误：expected primary-expression before ‘*’ token
 1252 | inline bool LoadTimeZone(absl::string_view name, TimeZone* tz) {
      |                                                          ^
/usr/include/absl/time/time.h:1252:60: 错误：‘tz’ was not declared in this scope; did you mean ‘tm’?
 1252 | inline bool LoadTimeZone(absl::string_view name, TimeZone* tz) {
      |                                                            ^~
      |                                                            tm
/usr/include/absl/time/time.h:1252:62: 错误：expression list treated as compound expression in initializer [-fpermissive]
 1252 | inline bool LoadTimeZone(absl::string_view name, TimeZone* tz) {
      |                                                              ^
/usr/include/absl/time/time.h:1494:59: 错误：‘string_view’不是‘absl’的成员
 1494 | ABSL_ATTRIBUTE_PURE_FUNCTION std::string FormatTime(absl::string_view format,
      |                                                           ^~~~~~~~~~~
/usr/include/absl/time/time.h:1495:58: 错误：expected primary-expression before ‘t’
 1495 |                                                     Time t, TimeZone tz);
      |                                                          ^
/usr/include/absl/time/time.h:1495:70: 错误：expected primary-expression before ‘tz’
 1495 |                                                     Time t, TimeZone tz);
      |                                                                      ^~
/usr/include/absl/time/time.h:1500:72: 错误：‘std::string absl::lts_20240722::FormatTime(Time, TimeZone)’ redeclared as different kind of entity
 1500 | ABSL_ATTRIBUTE_PURE_FUNCTION std::string FormatTime(Time t, TimeZone tz);
      |                                                                        ^
/usr/include/absl/time/time.h:1494:42: 附注：previous declaration ‘std::string absl::lts_20240722::FormatTime’
 1494 | ABSL_ATTRIBUTE_PURE_FUNCTION std::string FormatTime(absl::string_view format,
      |                                          ^~~~~~~~~~
/usr/include/absl/time/time.h:1501:59: 错误：‘std::string absl::lts_20240722::FormatTime(Time)’ redeclared as different kind of entity
 1501 | ABSL_ATTRIBUTE_PURE_FUNCTION std::string FormatTime(Time t);
      |                                                           ^
/usr/include/absl/time/time.h:1494:42: 附注：previous declaration ‘std::string absl::lts_20240722::FormatTime’
 1494 | ABSL_ATTRIBUTE_PURE_FUNCTION std::string FormatTime(absl::string_view format,
      |                                          ^~~~~~~~~~
/usr/include/absl/time/time.h: In function ‘std::ostream& absl::lts_20240722::operator<<(std::ostream&, Time)’:
/usr/include/absl/time/time.h:1505:26: 错误：对‘(std::string {aka std::__cxx11::basic_string<char>}) (absl::lts_20240722::Time&)’的调用没有匹配
 1505 |   return os << FormatTime(t);
      |                ~~~~~~~~~~^~~
/usr/include/absl/time/time.h: In function ‘void absl::lts_20240722::AbslStringify(Sink&, Time)’:
/usr/include/absl/time/time.h:1511:25: 错误：对‘(std::string {aka std::__cxx11::basic_string<char>}) (absl::lts_20240722::Time&)’的调用没有匹配
 1511 |   sink.Append(FormatTime(t));
      |               ~~~~~~~~~~^~~
/usr/include/absl/time/time.h: 在全局域：
/usr/include/absl/time/time.h:1563:22: 错误：‘string_view’不是‘absl’的成员
 1563 | bool ParseTime(absl::string_view format, absl::string_view input, Time* time,
      |                      ^~~~~~~~~~~
/usr/include/absl/time/time.h:1563:48: 错误：‘string_view’不是‘absl’的成员
 1563 | bool ParseTime(absl::string_view format, absl::string_view input, Time* time,
      |                                                ^~~~~~~~~~~
/usr/include/absl/time/time.h:1563:71: 错误：expected primary-expression before ‘*’ token
 1563 | bool ParseTime(absl::string_view format, absl::string_view input, Time* time,
      |                                                                       ^
/usr/include/absl/time/time.h:1564:27: 错误：expected primary-expression before ‘*’ token
 1564 |                std::string* err);
      |                           ^
/usr/include/absl/time/time.h:1564:29: 错误：‘err’ was not declared in this scope; did you mean ‘erf’?
 1564 |                std::string* err);
      |                             ^~~
      |                             erf
/usr/include/absl/time/time.h:1564:32: 错误：expression list treated as compound expression in initializer [-fpermissive]
 1564 |                std::string* err);
      |                                ^
/usr/include/absl/time/time.h:1573:6: 错误：‘bool absl::lts_20240722::ParseTime’ 重定义
 1573 | bool ParseTime(absl::string_view format, absl::string_view input, TimeZone tz,
      |      ^~~~~~~~~
/usr/include/absl/time/time.h:1563:6: 附注：‘bool absl::lts_20240722::ParseTime’ previously defined here
 1563 | bool ParseTime(absl::string_view format, absl::string_view input, Time* time,
      |      ^~~~~~~~~
/usr/include/absl/time/time.h:1573:22: 错误：‘string_view’不是‘absl’的成员
 1573 | bool ParseTime(absl::string_view format, absl::string_view input, TimeZone tz,
      |                      ^~~~~~~~~~~
/usr/include/absl/time/time.h:1573:48: 错误：‘string_view’不是‘absl’的成员
 1573 | bool ParseTime(absl::string_view format, absl::string_view input, TimeZone tz,
      |                                                ^~~~~~~~~~~
/usr/include/absl/time/time.h:1573:76: 错误：expected primary-expression before ‘tz’
 1573 | bool ParseTime(absl::string_view format, absl::string_view input, TimeZone tz,
      |                                                                            ^~
/usr/include/absl/time/time.h:1574:20: 错误：expected primary-expression before ‘*’ token
 1574 |                Time* time, std::string* err);
      |                    ^
/usr/include/absl/time/time.h:1574:39: 错误：expected primary-expression before ‘*’ token
 1574 |                Time* time, std::string* err);
      |                                       ^
/usr/include/absl/time/time.h:1574:41: 错误：‘err’ was not declared in this scope; did you mean ‘erf’?
 1574 |                Time* time, std::string* err);
      |                                         ^~~
      |                                         erf
/usr/include/absl/log/log_entry.h:75:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
   75 |   absl::string_view source_filename() const ABSL_ATTRIBUTE_LIFETIME_BOUND {
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:78:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
   78 |   absl::string_view source_basename() const ABSL_ATTRIBUTE_LIFETIME_BOUND {
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:145:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  145 |   absl::string_view text_message_with_prefix_and_newline() const
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:151:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  151 |   absl::string_view text_message_with_prefix() const
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:157:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  157 |   absl::string_view text_message_with_newline() const
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:163:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  163 |   absl::string_view text_message() const ABSL_ATTRIBUTE_LIFETIME_BOUND {
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:178:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  178 |   absl::string_view encoded_message() const ABSL_ATTRIBUTE_LIFETIME_BOUND {
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:194:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  194 |   absl::string_view stacktrace() const ABSL_ATTRIBUTE_LIFETIME_BOUND {
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:201:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  201 |   absl::string_view full_filename_;
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:202:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  202 |   absl::string_view base_filename_;
      |         ^~~~~~~~~~~
/usr/include/absl/log/log_entry.h:211:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  211 |   absl::string_view encoding_;
      |         ^~~~~~~~~~~
In file included from /usr/include/absl/log/internal/log_message.h:43:
/usr/include/absl/strings/has_absl_stringify.h:36:15: 错误：‘string_view’未声明
   36 |   void Append(string_view v);
      |               ^~~~~~~~~~~
/usr/include/absl/strings/has_absl_stringify.h:39:62: 错误：‘absl::string_view’尚未声明
   39 |   friend void AbslFormatFlush(UnimplementedSink* sink, absl::string_view v);
      |                                                              ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:75:32: 错误：‘absl::string_view’尚未声明
   75 |   LogMessage& AtLocation(absl::string_view file, int line);
      |                                ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:146:32: 错误：‘absl::string_view’尚未声明
  146 |   LogMessage& operator<<(absl::string_view v);
      |                                ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:146:15: 错误：‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(int)’ cannot be overloaded with ‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(int)’
  146 |   LogMessage& operator<<(absl::string_view v);
      |               ^~~~~~~~
/usr/include/absl/log/internal/log_message.h:118:15: 附注：previous declaration ‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(int)’
  118 |   LogMessage& operator<<(signed int v) { return operator<< <signed int>(v); }
      |               ^~~~~~~~
/usr/include/absl/log/internal/log_message.h:235:34: 错误：‘absl::string_view’尚未声明
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |                                  ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:271:21: 错误：‘absl::string_view’尚未声明
  271 |   void Append(absl::string_view v) {
      |                     ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:276:58: 错误：‘absl::string_view’尚未声明
  276 |   friend void AbslFormatFlush(StringifySink* sink, absl::string_view v) {
      |                                                          ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:341:45: 错误：模板标识符‘CopyToEncodedBuffer<absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral>’用作声明
  341 |     LogMessage::StringType::kLiteral>(absl::string_view str);
      |                                             ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:340:22: 错误：变量或字段‘CopyToEncodedBuffer’声明为 void
  340 | extern template void LogMessage::CopyToEncodedBuffer<
      |                      ^~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:341:38: 错误：expected ‘;’ before ‘(’ token
  341 |     LogMessage::StringType::kLiteral>(absl::string_view str);
      |                                      ^
      |                                      ;
/usr/include/absl/log/internal/log_message.h:343:48: 错误：模板标识符‘CopyToEncodedBuffer<absl::lts_20240722::log_internal::LogMessage::StringType::kNotLiteral>’用作声明
  343 |     LogMessage::StringType::kNotLiteral>(absl::string_view str);
      |                                                ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:342:22: 错误：变量或字段‘CopyToEncodedBuffer’声明为 void
  342 | extern template void LogMessage::CopyToEncodedBuffer<
      |                      ^~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:343:41: 错误：expected ‘;’ before ‘(’ token
  343 |     LogMessage::StringType::kNotLiteral>(absl::string_view str);
      |                                         ^
      |                                         ;
/usr/include/absl/log/internal/log_message.h:356:25: 错误：‘absl::string_view’尚未声明
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                         ^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:383:32: 错误：‘absl::string_view’尚未声明
  383 |                          absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                                ^~~~~~~~~~~
/usr/include/absl/log/internal/check_op.h:299:21: 错误：‘absl::string_view’尚未声明
  299 |   void Append(absl::string_view text);
      |                     ^~~~~~~~~~~
/usr/include/absl/log/internal/check_op.h:301:58: 错误：‘absl::string_view’尚未声明
  301 |   friend void AbslFormatFlush(StringifySink* sink, absl::string_view text);
      |                                                          ^~~~~~~~~~~
/usr/include/absl/log/internal/check_op.h:362:1: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  362 | ABSL_LOG_INTERNAL_DEFINE_MAKE_CHECK_OP_STRING_EXTERN(const absl::string_view&);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/check_op.h:362:1: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  362 | ABSL_LOG_INTERNAL_DEFINE_MAKE_CHECK_OP_STRING_EXTERN(const absl::string_view&);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /usr/include/absl/container/internal/compressed_tuple.h:40,
                 from /usr/include/absl/container/internal/inlined_vector.h:32,
                 from /usr/include/absl/container/inlined_vector.h:53,
                 from /usr/include/absl/strings/cord.h:80,
                 from /usr/include/google/protobuf/io/coded_stream.h:112:
/usr/include/absl/utility/utility.h:85:12: 错误：‘in_place_t’ has not been declared in ‘std’
   85 | using std::in_place_t;
      |            ^~~~~~~~~~
/usr/include/absl/utility/utility.h:86:12: 错误：‘in_place’ has not been declared in ‘std’
   86 | using std::in_place;
      |            ^~~~~~~~
/usr/include/absl/utility/utility.h:102:12: 错误：‘in_place_type’ has not been declared in ‘std’
  102 | using std::in_place_type;
      |            ^~~~~~~~~~~~~
/usr/include/absl/utility/utility.h:103:12: 错误：‘in_place_type_t’ has not been declared in ‘std’
  103 | using std::in_place_type_t;
      |            ^~~~~~~~~~~~~~~
/usr/include/absl/utility/utility.h:119:12: 错误：‘in_place_index’ has not been declared in ‘std’
  119 | using std::in_place_index;
      |            ^~~~~~~~~~~~~~
/usr/include/absl/utility/utility.h:120:12: 错误：‘in_place_index_t’ has not been declared in ‘std’
  120 | using std::in_place_index_t;
      |            ^~~~~~~~~~~~~~~~
/usr/include/absl/container/internal/compressed_tuple.h:89:46: 错误：expected ‘)’ before ‘,’ token
   89 |   explicit constexpr Storage(absl::in_place_t, V&& v)
      |                             ~                ^
      |                                              )
/usr/include/absl/container/internal/compressed_tuple.h:102:46: 错误：expected ‘)’ before ‘,’ token
  102 |   explicit constexpr Storage(absl::in_place_t, V&& v) : T(std::forward<V>(v)) {}
      |                             ~                ^
      |                                              )
/usr/include/absl/container/internal/compressed_tuple.h:124:58: 错误：expected ‘)’ before ‘,’ token
  124 |   explicit constexpr CompressedTupleImpl(absl::in_place_t, Vs&&... args)
      |                                         ~                ^
      |                                                          )
/usr/include/absl/container/internal/compressed_tuple.h:136:58: 错误：expected ‘)’ before ‘,’ token
  136 |   explicit constexpr CompressedTupleImpl(absl::in_place_t, Vs&&... args)
      |                                         ~                ^
      |                                                          )
/usr/include/absl/container/internal/compressed_tuple.h: In constructor ‘constexpr absl::lts_20240722::container_internal::CompressedTuple<Ts>::CompressedTuple(const Ts& ...)’:
/usr/include/absl/container/internal/compressed_tuple.h:223:52: 错误：‘in_place’不是‘absl’的成员
  223 |       : CompressedTuple::CompressedTupleImpl(absl::in_place, base...) {}
      |                                                    ^~~~~~~~
/usr/include/absl/container/internal/compressed_tuple.h: In constructor ‘constexpr absl::lts_20240722::container_internal::CompressedTuple<Ts>::CompressedTuple(First&&, Vs&& ...)’:
/usr/include/absl/container/internal/compressed_tuple.h:235:52: 错误：‘in_place’不是‘absl’的成员
  235 |       : CompressedTuple::CompressedTupleImpl(absl::in_place,
      |                                                    ^~~~~~~~
In file included from /usr/include/absl/strings/internal/str_format/extension.h:27,
                 from /usr/include/absl/strings/internal/str_format/arg.h:37,
                 from /usr/include/absl/strings/str_format.h:83,
                 from /usr/include/absl/crc/crc32c.h:32,
                 from /usr/include/absl/crc/internal/crc_cord_state.h:23,
                 from /usr/include/absl/strings/cord.h:81:
/usr/include/absl/strings/internal/str_format/output.h: 在全局域：
/usr/include/absl/strings/internal/str_format/output.h:44:14: 错误：‘string_view’未声明
   44 |   void Write(string_view v);
      |              ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/output.h:59:14: 错误：‘string_view’未声明
   59 |   void Write(string_view v);
      |              ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/output.h:71:47: 错误：‘string_view’未声明
   71 | inline void AbslFormatFlush(std::string* out, string_view s) {
      |                                               ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/output.h: In function ‘void absl::lts_20240722::str_format_internal::AbslFormatFlush(std::string*, int)’:
/usr/include/absl/strings/internal/str_format/output.h:72:17: 错误：对成员‘data’的请求出现在‘s’中，而后者具有非类类型‘int’
   72 |   out->append(s.data(), s.size());
      |                 ^~~~
/usr/include/absl/strings/internal/str_format/output.h:72:27: 错误：对成员‘size’的请求出现在‘s’中，而后者具有非类类型‘int’
   72 |   out->append(s.data(), s.size());
      |                           ^~~~
/usr/include/absl/strings/internal/str_format/output.h: 在全局域：
/usr/include/absl/strings/internal/str_format/output.h:74:48: 错误：‘string_view’未声明
   74 | inline void AbslFormatFlush(std::ostream* out, string_view s) {
      |                                                ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/output.h: In function ‘void absl::lts_20240722::str_format_internal::AbslFormatFlush(std::ostream*, int)’:
/usr/include/absl/strings/internal/str_format/output.h:75:16: 错误：对成员‘data’的请求出现在‘s’中，而后者具有非类类型‘int’
   75 |   out->write(s.data(), static_cast<std::streamsize>(s.size()));
      |                ^~~~
/usr/include/absl/strings/internal/str_format/output.h:75:55: 错误：对成员‘size’的请求出现在‘s’中，而后者具有非类类型‘int’
   75 |   out->write(s.data(), static_cast<std::streamsize>(s.size()));
      |                                                       ^~~~
/usr/include/absl/strings/internal/str_format/output.h: 在全局域：
/usr/include/absl/strings/internal/str_format/output.h:78:48: 错误：‘string_view’未声明
   78 | inline void AbslFormatFlush(FILERawSink* sink, string_view v) {
      |                                                ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/output.h:82:50: 错误：‘string_view’未声明
   82 | inline void AbslFormatFlush(BufferRawSink* sink, string_view v) {
      |                                                  ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/output.h:89:26: 错误：‘string_view’未声明
   89 | auto InvokeFlush(T* out, string_view s) -> decltype(AbslFormatFlush(out, s)) {
      |                          ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h:44:49: 错误：‘string_view’的实参不依赖模板参数，所以‘string_view’的声明必须可用 [-fpermissive]
   44 |                             std::declval<T*>(), string_view()))* = nullptr>
      |                                                 ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h:44:49: 附注：(如果您使用‘-fpermissive’，G++ 会接受您的代码，但是允许使用未定义的名称是已弃用的风格)
/usr/include/absl/strings/internal/str_format/extension.h:44:49: 错误：‘string_view’的实参不依赖模板参数，所以‘string_view’的声明必须可用 [-fpermissive]
/usr/include/absl/strings/internal/str_format/extension.h:48:14: 错误：‘string_view’未声明
   48 |   void Write(string_view s) { write_(sink_, s); }
      |              ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h:57:30: 错误：‘string_view’未声明
   57 |   static void Flush(void* r, string_view s) {
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h:62:25: 错误：‘string_view’未声明
   62 |   void (*write_)(void*, string_view);
      |                         ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h:94:15: 错误：‘string_view’未声明
   94 |   void Append(string_view v) {
      |               ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h:110:24: 错误：‘string_view’未声明
  110 |   bool PutPaddedString(string_view v, int width, int precision, bool left);
      |                        ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h: In member function ‘void absl::lts_20240722::str_format_internal::FormatSinkImpl::Flush()’:
/usr/include/absl/strings/internal/str_format/extension.h:73:16: 错误：‘string_view’在此作用域中尚未声明
   73 |     raw_.Write(string_view(buf_, static_cast<size_t>(pos_ - buf_)));
      |                ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/extension.h: In member function ‘void absl::lts_20240722::str_format_internal::FormatSinkImpl::Append(int)’:
/usr/include/absl/strings/internal/str_format/extension.h:95:18: 错误：对成员‘size’的请求出现在‘v’中，而后者具有非类类型‘int’
   95 |     size_t n = v.size();
      |                  ^~~~
/usr/include/absl/strings/internal/str_format/extension.h:103:20: 错误：对成员‘data’的请求出现在‘v’中，而后者具有非类类型‘int’
  103 |     memcpy(pos_, v.data(), n);
      |                    ^~~~
/usr/include/absl/strings/internal/str_format/arg.h: 在全局域：
/usr/include/absl/strings/internal/str_format/arg.h:228:39: 错误：‘absl::lts_20240722::str_format_internal::StringConvertResult absl::lts_20240722::str_format_internal::FormatConvertImpl’ redeclared as different kind of entity
  228 | StringConvertResult FormatConvertImpl(string_view v,
      |                                       ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/arg.h:225:21: 附注：previous declaration ‘absl::lts_20240722::str_format_internal::StringConvertResult absl::lts_20240722::str_format_internal::FormatConvertImpl(const std::wstring&, FormatConversionSpecImpl, FormatSinkImpl*)’
  225 | StringConvertResult FormatConvertImpl(const std::wstring& v,
      |                     ^~~~~~~~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/arg.h:228:39: 错误：‘string_view’在此作用域中尚未声明
  228 | StringConvertResult FormatConvertImpl(string_view v,
      |                                       ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/arg.h:229:64: 错误：expected primary-expression before ‘conv’
  229 |                                       FormatConversionSpecImpl conv,
      |                                                                ^~~~
/usr/include/absl/strings/internal/str_format/arg.h:230:53: 错误：expected primary-expression before ‘*’ token
  230 |                                       FormatSinkImpl* sink);
      |                                                     ^
/usr/include/absl/strings/internal/str_format/arg.h:230:55: 错误：‘sink’ was not declared in this scope; did you mean ‘sinl’?
  230 |                                       FormatSinkImpl* sink);
      |                                                       ^~~~
      |                                                       sinl
/usr/include/absl/strings/internal/str_format/arg.h: In function ‘absl::lts_20240722::str_format_internal::StringConvertResult absl::lts_20240722::str_format_internal::FormatConvertImpl(const AbslCord&, FormatConversionSpecImpl, FormatSinkImpl*)’:
/usr/include/absl/strings/internal/str_format/arg.h:280:8: 错误：‘string_view’在此作用域中尚未声明
  280 |   for (string_view piece : value.Chunks()) {
      |        ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/arg.h:293:3: 错误：expected primary-expression before ‘if’
  293 |   if (space_remaining > 0 && is_left) sink->Append(space_remaining, ' ');
      |   ^~
/usr/include/absl/strings/internal/str_format/arg.h:291:4: 错误：expected ‘;’ before ‘if’
  291 |   }
      |    ^
      |    ;
  292 | 
  293 |   if (space_remaining > 0 && is_left) sink->Append(space_remaining, ' ');
      |   ~~
/usr/include/absl/strings/internal/str_format/arg.h:293:3: 错误：expected primary-expression before ‘if’
  293 |   if (space_remaining > 0 && is_left) sink->Append(space_remaining, ' ');
      |   ^~
/usr/include/absl/strings/internal/str_format/arg.h:291:4: 错误：expected ‘)’ before ‘if’
  291 |   }
      |    ^
      |    )
  292 | 
  293 |   if (space_remaining > 0 && is_left) sink->Append(space_remaining, ' ');
      |   ~~
/usr/include/absl/strings/internal/str_format/arg.h:280:7: 附注：to match this ‘(’
  280 |   for (string_view piece : value.Chunks()) {
      |       ^
/usr/include/absl/strings/internal/str_format/arg.h: 在全局域：
/usr/include/absl/strings/internal/str_format/arg.h:664:1: 错误：‘string_view’在此作用域中尚未声明
  664 | ABSL_INTERNAL_FORMAT_DISPATCH_OVERLOADS_EXPAND_(extern);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/arg.h:664:1: 错误：‘bool absl::lts_20240722::str_format_internal::FormatArgImpl::Dispatch(Data, absl::lts_20240722::str_format_internal::FormatConversionSpecImpl, void*)’的模板标识符‘Dispatch<<表达式错误> >’不匹配任何模板声明
  664 | ABSL_INTERNAL_FORMAT_DISPATCH_OVERLOADS_EXPAND_(extern);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/arg.h:599:15: 附注：备选是： ‘template<class T> static bool absl::lts_20240722::str_format_internal::FormatArgImpl::Dispatch(Data, absl::lts_20240722::str_format_internal::FormatConversionSpecImpl, void*)’
  599 |   static bool Dispatch(Data arg, FormatConversionSpecImpl spec, void* out) {
      |               ^~~~~~~~
In file included from /usr/include/absl/strings/internal/str_format/bind.h:29,
                 from /usr/include/absl/strings/str_format.h:84:
/usr/include/absl/strings/internal/str_format/parser.h:57:24: 错误：‘string_view’在此作用域中尚未声明
   57 | bool ParseFormatString(string_view src, Consumer consumer) {
      |                        ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/parser.h:57:50: 错误：expected primary-expression before ‘consumer’
   57 | bool ParseFormatString(string_view src, Consumer consumer) {
      |                                                  ^~~~~~~~
/usr/include/absl/strings/internal/str_format/parser.h:57:58: 错误：expression list treated as compound expression in initializer [-fpermissive]
   57 | bool ParseFormatString(string_view src, Consumer consumer) {
      |                                                          ^
/usr/include/absl/strings/internal/str_format/parser.h:57:59: 错误：expected ‘;’ before ‘{’ token
   57 | bool ParseFormatString(string_view src, Consumer consumer) {
      |                                                           ^~
      |                                                           ;
/usr/include/absl/strings/internal/str_format/parser.h:116:32: 错误：‘string_view’在此作用域中尚未声明
  116 | constexpr bool EnsureConstexpr(string_view s) {
      |                                ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/parser.h:123:18: 错误：expected ‘)’ before ‘format’
  123 |       string_view format, bool allow_ignored,
      |                  ^~~~~~~
      |                  )
/usr/include/absl/strings/internal/str_format/parser.h:122:28: 附注：to match this ‘(’
  122 |   explicit ParsedFormatBase(
      |                            ^
/usr/include/absl/strings/internal/str_format/parser.h: In member function ‘bool absl::lts_20240722::str_format_internal::ParsedFormatBase::ProcessFormat(Consumer) const’:
/usr/include/absl/strings/internal/str_format/parser.h:153:5: 错误：‘string_view’在此作用域中尚未声明
  153 |     string_view text(base, 0);
      |     ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/parser.h:155:31: 错误：‘text’在此作用域中尚未声明
  155 |       const char* const end = text.data() + text.size();
      |                               ^~~~
/usr/include/absl/strings/internal/str_format/parser.h: 在全局域：
/usr/include/absl/strings/internal/str_format/parser.h:222:44: 错误：expected ‘)’ before ‘format’
  222 |   explicit ExtendedParsedFormat(string_view format)
      |                                ~           ^~~~~~~
      |                                            )
/usr/include/absl/strings/internal/str_format/parser.h:245:52: 错误：‘string_view’未声明
  245 |   static std::unique_ptr<ExtendedParsedFormat> New(string_view format) {
      |                                                    ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/parser.h:249:7: 错误：‘string_view’未声明
  249 |       string_view format) {
      |       ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/parser.h:254:52: 错误：‘string_view’未声明
  254 |   static std::unique_ptr<ExtendedParsedFormat> New(string_view format,
      |                                                    ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/parser.h:262:35: 错误：expected ‘)’ before ‘s’
  262 |   ExtendedParsedFormat(string_view s, bool allow_ignored)
      |                       ~           ^~
      |                                   )
/usr/include/absl/strings/internal/str_format/parser.h:263:50: 错误：expected unqualified-id before ‘)’ token
  263 |       : ParsedFormatBase(s, allow_ignored, {C...}) {}
      |                                                  ^
/usr/include/absl/strings/internal/str_format/bind.h:55:45: 错误：expected ‘)’ before ‘s’
   55 |   explicit UntypedFormatSpecImpl(string_view s)
      |                                 ~           ^~
      |                                             )
/usr/include/absl/strings/internal/str_format/bind.h:63:3: 错误：‘string_view’不是一个类型名
   63 |   string_view str() const {
      |   ^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/bind.h:168:33: 错误：expected ‘)’ before ‘s’
  168 |   FormatSpecTemplate(string_view s) : Base(s) {}  // NOLINT
      |                     ~           ^~
      |                                 )
/usr/include/absl/strings/str_format.h:111:41: 错误：expected ‘)’ before ‘s’
  111 |   explicit UntypedFormatSpec(string_view s) : spec_(s) {}
      |                             ~           ^~
      |                                         )
/usr/include/absl/strings/str_format.h:847:15: 错误：‘string_view’未声明
  847 |   void Append(string_view v) { sink_->Append(v); }
      |               ^~~~~~~~~~~
/usr/include/absl/strings/str_format.h:855:24: 错误：‘string_view’未声明
  855 |   bool PutPaddedString(string_view v, int width, int precision, bool left) {
      |                        ^~~~~~~~~~~
/usr/include/absl/strings/str_format.h:861:37: 错误：‘absl::string_view’尚未声明
  861 |                               absl::string_view v) {
      |                                     ^~~~~~~~~~~
/usr/include/absl/crc/crc32c.h:79:37: 错误：‘absl::string_view’尚未声明
   79 |                               absl::string_view buf_to_add);
      |                                     ^~~~~~~~~~~
/usr/include/absl/crc/crc32c.h:89:30: 错误：‘string_view’不是‘absl’的成员
   89 | crc32c_t ComputeCrc32c(absl::string_view buf);
      |                              ^~~~~~~~~~~
/usr/include/absl/crc/crc32c.h:103:36: 错误：‘absl::string_view’尚未声明
  103 |                              absl::string_view buf_to_add) {
      |                                    ^~~~~~~~~~~
/usr/include/absl/crc/crc32c.h: In function ‘absl::lts_20240722::crc32c_t absl::lts_20240722::ExtendCrc32c(crc32c_t, int)’:
/usr/include/absl/crc/crc32c.h:105:18: 错误：对成员‘size’的请求出现在‘buf_to_add’中，而后者具有非类类型‘int’
  105 |   if (buf_to_add.size() <= 64) {
      |                  ^~~~
/usr/include/absl/crc/crc32c.h:107:59: 错误：对成员‘data’的请求出现在‘buf_to_add’中，而后者具有非类类型‘int’
  107 |     if (crc_internal::ExtendCrc32cInline(&crc, buf_to_add.data(),
      |                                                           ^~~~
/usr/include/absl/crc/crc32c.h:108:53: 错误：对成员‘size’的请求出现在‘buf_to_add’中，而后者具有非类类型‘int’
  108 |                                          buf_to_add.size())) {
      |                                                     ^~~~
In file included from /usr/include/absl/functional/any_invocable.h:43,
                 from /usr/include/absl/functional/internal/function_ref.h:23,
                 from /usr/include/absl/functional/function_ref.h:54,
                 from /usr/include/absl/strings/cord.h:82:
/usr/include/absl/functional/internal/any_invocable.h: 在全局域：
/usr/include/absl/functional/internal/any_invocable.h:380:28: 错误：‘in_place_type_t’不是‘absl’的成员
  380 | struct IsInPlaceType<absl::in_place_type_t<T>> : std::true_type {};
      |                            ^~~~~~~~~~~~~~~
/usr/include/absl/functional/internal/any_invocable.h:380:28: 错误：‘in_place_type_t’不是‘absl’的成员
/usr/include/absl/functional/internal/any_invocable.h:380:44: 错误：模板第 1 个参数无效
  380 | struct IsInPlaceType<absl::in_place_type_t<T>> : std::true_type {};
      |                                            ^
/usr/include/absl/functional/internal/any_invocable.h:380:45: 错误：expected unqualified-id before ‘>’ token
  380 | struct IsInPlaceType<absl::in_place_type_t<T>> : std::true_type {};
      |                                             ^~
/usr/include/absl/functional/internal/any_invocable.h:476:42: 错误：expected ‘)’ before ‘<’ token
  476 |   explicit CoreImpl(absl::in_place_type_t<QualTRef>, Args&&... args) {
      |                    ~                     ^
      |                                          )
/usr/include/absl/functional/internal/any_invocable.h:868:1: 错误：expected ‘)’ before ‘<’ token
  868 | ABSL_INTERNAL_ANY_INVOCABLE_IMPL(, , &);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/functional/internal/any_invocable.h:869:1: 错误：expected ‘)’ before ‘<’ token
  869 | ABSL_INTERNAL_ANY_INVOCABLE_IMPL(const, , const&);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/functional/internal/any_invocable.h:872:1: 错误：expected ‘)’ before ‘<’ token
  872 | ABSL_INTERNAL_ANY_INVOCABLE_IMPL(, &, &);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/functional/internal/any_invocable.h:873:1: 错误：expected ‘)’ before ‘<’ token
  873 | ABSL_INTERNAL_ANY_INVOCABLE_IMPL(const, &, const&);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/functional/internal/any_invocable.h:876:1: 错误：expected ‘)’ before ‘<’ token
  876 | ABSL_INTERNAL_ANY_INVOCABLE_IMPL(, &&, &&);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/functional/internal/any_invocable.h:877:1: 错误：expected ‘)’ before ‘<’ token
  877 | ABSL_INTERNAL_ANY_INVOCABLE_IMPL(const, &&, const&&);
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/functional/any_invocable.h:208:46: 错误：expected ‘)’ before ‘<’ token
  208 |   explicit AnyInvocable(absl::in_place_type_t<T>, Args&&... args)
      |                        ~                     ^
      |                                              )
/usr/include/absl/functional/any_invocable.h:220:46: 错误：expected ‘)’ before ‘<’ token
  220 |   explicit AnyInvocable(absl::in_place_type_t<T>,
      |                        ~                     ^
      |                                              )
In file included from /usr/include/absl/strings/cord_analysis.h:23,
                 from /usr/include/absl/strings/cord.h:84:
/usr/include/absl/strings/internal/cord_internal.h:341:55: 错误：expected ‘)’ before ‘str’
  341 |   explicit constexpr CordRepExternal(absl::string_view str)
      |                                     ~                 ^~~~
      |                                                       )
/usr/include/absl/strings/internal/cord_internal.h:342:45: 错误：expected unqualified-id before ‘,’ token
  342 |       : CordRep(RefcountAndFlags::Immortal{}, str.size()),
      |                                             ^
/usr/include/absl/strings/internal/cord_internal.h:360:50: 错误：‘string_view’不是‘absl’的成员
  360 |                                  Releaser, absl::string_view>>
      |                                                  ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_internal.h:360:50: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/strings/internal/cord_internal.h:360:50: 错误：模板第 2 个参数无效
/usr/include/absl/strings/internal/cord_internal.h:361:55: 错误：‘absl::string_view’尚未声明
  361 | void InvokeReleaser(Rank1, Releaser&& releaser, absl::string_view data) {
      |                                                       ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_internal.h:367:55: 错误：‘absl::string_view’尚未声明
  367 | void InvokeReleaser(Rank0, Releaser&& releaser, absl::string_view) {
      |                                                       ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_internal.h: In destructor ‘absl::lts_20240722::cord_internal::CordRepExternalImpl<Releaser>::~CordRepExternalImpl()’:
/usr/include/absl/strings/internal/cord_internal.h:386:26: 错误：‘string_view’不是‘absl’的成员
  386 |                    absl::string_view(base, length));
      |                          ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_internal.h: 在全局域：
/usr/include/absl/strings/internal/cord_internal.h:454:32: 错误：‘string_view’不是‘absl’的成员
  454 | constexpr char GetOrNull(absl::string_view data, size_t pos) {
      |                                ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_internal.h:454:57: 错误：expected primary-expression before ‘pos’
  454 | constexpr char GetOrNull(absl::string_view data, size_t pos) {
      |                                                         ^~~
/usr/include/absl/strings/internal/cord_internal.h:454:60: 错误：expression list treated as compound expression in initializer [-fpermissive]
  454 | constexpr char GetOrNull(absl::string_view data, size_t pos) {
      |                                                            ^
/usr/include/absl/strings/internal/cord_internal.h:516:41: 错误：expected ‘)’ before ‘sv’
  516 |   constexpr InlineData(absl::string_view sv, CordRep* rep) noexcept
      |                       ~                 ^~~
      |                                         )
/usr/include/absl/strings/internal/cord_internal.h:698:45: 错误：expected ‘)’ before ‘chars’
  698 |     explicit constexpr Rep(absl::string_view chars)
      |                           ~                 ^~~~~~
      |                                             )
/usr/include/absl/strings/internal/cord_internal.h:714:38: 错误：expected unqualified-id before ‘{’ token
  714 |                GetOrNull(chars, 14)} {}
      |                                      ^
In file included from /usr/include/absl/strings/cord_buffer.h:38,
                 from /usr/include/absl/strings/cord.h:85:
/usr/include/absl/strings/internal/cord_rep_flat.h:161:36: 错误：‘absl::string_view’尚未声明
  161 |   static CordRepFlat* Create(absl::string_view data, size_t extra = 0) {
      |                                    ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_flat.h: In static member function ‘static absl::lts_20240722::cord_internal::CordRepFlat* absl::lts_20240722::cord_internal::CordRepFlat::Create(int, size_t)’:
/usr/include/absl/strings/internal/cord_rep_flat.h:163:34: 错误：对成员‘size’的请求出现在‘data’中，而后者具有非类类型‘int’
  163 |     CordRepFlat* flat = New(data.size() + (std::min)(extra, kMaxFlatLength));
      |                                  ^~~~
/usr/include/absl/strings/internal/cord_rep_flat.h:164:31: 错误：对成员‘data’的请求出现在‘data’中，而后者具有非类类型‘int’
  164 |     memcpy(flat->Data(), data.data(), data.size());
      |                               ^~~~
/usr/include/absl/strings/internal/cord_rep_flat.h:164:44: 错误：对成员‘size’的请求出现在‘data’中，而后者具有非类类型‘int’
  164 |     memcpy(flat->Data(), data.data(), data.size());
      |                                            ^~~~
/usr/include/absl/strings/internal/cord_rep_flat.h:165:25: 错误：对成员‘size’的请求出现在‘data’中，而后者具有非类类型‘int’
  165 |     flat->length = data.size();
      |                         ^~~~
/usr/include/absl/strings/cord_buffer.h: 在全局域：
/usr/include/absl/strings/cord_buffer.h:435:46: 错误：‘absl::string_view’尚未声明
  435 |   cord_internal::CordRep* ConsumeValue(absl::string_view& short_value) {
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/cord_buffer.h: In member function ‘absl::lts_20240722::cord_internal::CordRep* absl::lts_20240722::CordBuffer::ConsumeValue(int&)’:
/usr/include/absl/strings/cord_buffer.h:438:27: 错误：‘string_view’不是‘absl’的成员
  438 |       short_value = absl::string_view(rep_.data(), rep_.short_length());
      |                           ^~~~~~~~~~~
In file included from /usr/include/absl/strings/cord.h:86:
/usr/include/absl/strings/internal/cord_data_edge.h: 在全局域：
/usr/include/absl/strings/internal/cord_data_edge.h:45:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
   45 | inline absl::string_view EdgeData(const CordRep* edge) {
      |              ^~~~~~~~~~~
In file included from /usr/include/absl/strings/cord.h:88:
/usr/include/absl/strings/internal/cord_rep_btree.h:208:51: 错误：‘string_view’未声明
  208 |   static CordRepBtree* Append(CordRepBtree* tree, string_view data,
      |                                                   ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:210:52: 错误：‘string_view’未声明
  210 |   static CordRepBtree* Prepend(CordRepBtree* tree, string_view data,
      |                                                    ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:239:21: 错误：‘absl::string_view’尚未声明
  239 |   bool IsFlat(absl::string_view* fragment) const;
      |                     ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:245:46: 错误：‘absl::string_view’尚未声明
  245 |   bool IsFlat(size_t offset, size_t n, absl::string_view* fragment) const;
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:321:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  321 |   inline absl::string_view Data(size_t index) const;
      |                ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:346:46: 错误：‘absl::string_view’尚未声明
  346 |   static void Dump(const CordRep* rep, absl::string_view label,
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:348:46: 错误：‘absl::string_view’尚未声明
  348 |   static void Dump(const CordRep* rep, absl::string_view label,
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:455:38: 错误：‘absl::string_view’尚未声明
  455 |   static CordRepBtree* NewLeaf(absl::string_view data, size_t extra);
      |                                      ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:535:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  535 |   absl::string_view AddData(absl::string_view data, size_t extra);
      |         ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:571:58: 错误：‘absl::string_view’尚未声明
  571 |   static CordRepBtree* AddData(CordRepBtree* tree, absl::string_view data,
      |                                                          ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree.h:637:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  637 | inline absl::string_view CordRepBtree::Data(size_t index) const {
      |              ^~~~~~~~~~~
In file included from /usr/include/absl/strings/cord.h:89:
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:112:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  112 |   absl::string_view Init(CordRepBtree* tree);
      |         ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:118:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  118 |   absl::string_view Next();
      |         ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:122:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  122 |   absl::string_view Skip(size_t skip);
      |         ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:146:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  146 |   absl::string_view Read(size_t n, size_t chunk_size, CordRep*& tree);
      |         ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:155:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  155 |   absl::string_view Seek(size_t offset);
      |         ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:167:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  167 | inline absl::string_view CordRepBtreeReader::Init(CordRepBtree* tree) {
      |              ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:174:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  174 | inline absl::string_view CordRepBtreeReader::Next() {
      |              ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:182:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  182 | inline absl::string_view CordRepBtreeReader::Skip(size_t skip) {
      |              ^~~~~~~~~~~
/usr/include/absl/strings/internal/cord_rep_btree_reader.h:197:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  197 | inline absl::string_view CordRepBtreeReader::Seek(size_t offset) {
      |              ^~~~~~~~~~~
In file included from /usr/include/absl/strings/cord.h:97:
/usr/include/absl/strings/internal/string_constant.h:39:48: 错误：‘absl::string_view’尚未声明
   39 |   static constexpr bool TryConstexprEval(absl::string_view view) {
      |                                                ^~~~~~~~~~~
/usr/include/absl/strings/internal/string_constant.h:44:26: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
   44 |   static constexpr absl::string_view value = T{}();
      |                          ^~~~~~~~~~~
/usr/include/absl/strings/internal/string_constant.h:44:50: 错误：expected unqualified-id before ‘)’ token
   44 |   static constexpr absl::string_view value = T{}();
      |                                                  ^
/usr/include/absl/strings/internal/string_constant.h:45:19: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
   45 |   constexpr absl::string_view operator()() const { return value; }
      |                   ^~~~~~~~~~~
/usr/include/absl/strings/internal/string_constant.h:49:34: 错误：‘value’在此作用域中尚未声明
   49 |   static_assert(TryConstexprEval(value),
      |                                  ^~~~~
/usr/include/absl/strings/internal/string_constant.h: In static member function ‘static constexpr bool absl::lts_20240722::strings_internal::StringConstant<T>::TryConstexprEval(int)’:
/usr/include/absl/strings/internal/string_constant.h:40:17: 错误：对成员‘empty’的请求出现在‘view’中，而后者具有非类类型‘int’
   40 |     return view.empty() || 2 * view[0] != 1;
      |                 ^~~~~
/usr/include/absl/strings/internal/string_constant.h:40:36: 错误：‘int[int]’用作数组下标类型无效
   40 |     return view.empty() || 2 * view[0] != 1;
      |                                    ^
/usr/include/absl/strings/internal/string_constant.h: 在全局域：
/usr/include/absl/strings/internal/string_constant.h:55:17: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
   55 | constexpr absl::string_view StringConstant<T>::value;
      |                 ^~~~~~~~~~~
In file included from /usr/include/absl/strings/cord.h:100:
/usr/include/absl/types/optional.h:47:12: 错误：‘bad_optional_access’ has not been declared in ‘std’
   47 | using std::bad_optional_access;
      |            ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/types/optional.h:48:12: 错误：‘optional’ has not been declared in ‘std’
   48 | using std::optional;
      |            ^~~~~~~~
/usr/include/absl/types/optional.h:49:12: 错误：‘make_optional’ has not been declared in ‘std’
   49 | using std::make_optional;
      |            ^~~~~~~~~~~~~
/usr/include/absl/types/optional.h:50:12: 错误：‘nullopt_t’ has not been declared in ‘std’
   50 | using std::nullopt_t;
      |            ^~~~~~~~~
/usr/include/absl/types/optional.h:51:12: 错误：‘nullopt’ has not been declared in ‘std’
   51 | using std::nullopt;
      |            ^~~~~~~
/usr/include/absl/strings/cord.h:107:33: 错误：‘string_view’不是‘absl’的成员
  107 | Cord MakeCordFromExternal(absl::string_view, Releaser&&);
      |                                 ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:107:54: 错误：expected primary-expression before ‘&&’ token
  107 | Cord MakeCordFromExternal(absl::string_view, Releaser&&);
      |                                                      ^~
/usr/include/absl/strings/cord.h:107:56: 错误：expected primary-expression before ‘)’ token
  107 | Cord MakeCordFromExternal(absl::string_view, Releaser&&);
      |                                                        ^
/usr/include/absl/strings/cord.h:196:34: 错误：expected ‘)’ before ‘src’
  196 |   explicit Cord(absl::string_view src);
      |                ~                 ^~~~
      |                                  )
/usr/include/absl/strings/cord.h:197:25: 错误：‘absl::string_view’尚未声明
  197 |   Cord& operator=(absl::string_view src);
      |                         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:254:42: 错误：‘absl::string_view’尚未声明
  254 |   friend Cord MakeCordFromExternal(absl::string_view data, Releaser&& releaser);
      |                                          ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:254:79: 错误：‘template<class Releaser> absl::lts_20240722::Cord absl::lts_20240722::MakeCordFromExternal(int, Releaser&&)’ conflicts with a previous declaration
  254 |   friend Cord MakeCordFromExternal(absl::string_view data, Releaser&& releaser);
      |                                                                               ^
/usr/include/absl/strings/cord.h:107:6: 附注：previous declaration ‘template<class Releaser> absl::lts_20240722::Cord absl::lts_20240722::MakeCordFromExternal<Releaser>’
  107 | Cord MakeCordFromExternal(absl::string_view, Releaser&&);
      |      ^~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:268:21: 错误：‘absl::string_view’尚未声明
  268 |   void Append(absl::string_view src);
      |                     ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:329:22: 错误：‘absl::string_view’尚未声明
  329 |   void Prepend(absl::string_view src);
      |                      ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:387:21: 错误：‘absl::string_view’尚未声明
  387 |   int Compare(absl::string_view rhs) const;
      |                     ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:394:25: 错误：‘absl::string_view’尚未声明
  394 |   bool StartsWith(absl::string_view rhs) const;
      |                         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:399:23: 错误：‘absl::string_view’尚未声明
  399 |   bool EndsWith(absl::string_view rhs) const;
      |                       ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:405:23: 错误：‘absl::string_view’尚未声明
  405 |   bool Contains(absl::string_view rhs) const;
      |                       ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:471:30: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  471 |     using value_type = absl::string_view;
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:473:52: 错误：模板第 1 个参数无效
  473 |     using pointer = absl::Nonnull<const value_type*>;
      |                                                    ^
/usr/include/absl/strings/cord.h:474:23: 错误：‘value_type’不是一个类型名
  474 |     using reference = value_type;
      |                       ^~~~~~~~~~
/usr/include/absl/strings/cord.h:482:5: 错误：‘reference’不是一个类型名
  482 |     reference operator*() const;
      |     ^~~~~~~~~
/usr/include/absl/strings/cord.h:483:5: 错误：‘pointer’不是一个类型名
  483 |     pointer operator->() const;
      |     ^~~~~~~
/usr/include/absl/strings/cord.h:514:11: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  514 |     absl::string_view current_chunk_;
      |           ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:569:30: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  569 |     using value_type = absl::string_view;
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:570:23: 错误：‘value_type’不是一个类型名
  570 |     using reference = value_type&;
      |                       ^~~~~~~~~~
/usr/include/absl/strings/cord.h:571:34: 错误：expected ‘;’ before ‘value_type’
  571 |     using const_reference = const value_type&;
      |                                  ^~~~~~~~~~~
      |                                  ;
/usr/include/absl/strings/cord.h:675:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  675 |   static absl::string_view ChunkRemaining(const CharIterator& it);
      |                ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:763:9: 错误：‘optional’ in namespace ‘absl’ does not name a template type
  763 |   absl::optional<absl::string_view> TryFlat() const
      |         ^~~~~~~~
/usr/include/absl/strings/cord.h:771:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  771 |   absl::string_view Flatten() ABSL_ATTRIBUTE_LIFETIME_BOUND;
      |         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:778:27: 错误：‘absl::string_view’尚未声明
  778 |   CharIterator Find(absl::string_view needle) const;
      |                           ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:783:37: 错误：‘absl::string_view’尚未声明
  783 |                               absl::string_view part) {
      |                                     ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:816:9: 错误：‘optional’ in namespace ‘absl’ does not name a template type
  816 |   absl::optional<uint32_t> ExpectedChecksum() const;
      |         ^~~~~~~~
/usr/include/absl/strings/cord.h:847:34: 错误：expected ‘)’ before ‘src’
  847 |   explicit Cord(absl::string_view src, MethodIdentifier method);
      |                ~                 ^~~~
      |                                  )
/usr/include/absl/strings/cord.h:851:49: 错误：‘absl::string_view’尚未声明
  851 |   friend bool operator==(const Cord& lhs, absl::string_view rhs);
      |                                                 ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:890:50: 错误：‘string_view’不是‘absl’的成员
  890 |   void ForEachChunk(absl::FunctionRef<void(absl::string_view)>) const;
      |                                                  ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:890:62: 错误：模板第 1 个参数无效
  890 |   void ForEachChunk(absl::FunctionRef<void(absl::string_view)>) const;
      |                                                              ^
/usr/include/absl/strings/cord.h:894:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  894 |   absl::string_view FlattenSlowPath();
      |         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:913:51: 错误：expected ‘)’ before ‘sv’
  913 |     explicit constexpr InlineRep(absl::string_view sv,
      |                                 ~                 ^~~
      |                                                   )
/usr/include/absl/strings/cord.h:932:28: 错误：‘absl::string_view’尚未声明
  932 |     void AppendArray(absl::string_view src, MethodIdentifier method);
      |                            ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:933:11: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  933 |     absl::string_view FindFlatStartPiece() const;
      |           ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1045:46: 错误：‘string_view’不是‘absl’的成员
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1045:46: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/strings/cord.h:1045:58: 错误：模板第 1 个参数无效
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                                          ^
/usr/include/absl/strings/cord.h:1045:46: 错误：‘string_view’不是‘absl’的成员
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1045:46: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/strings/cord.h:1045:58: 错误：模板第 1 个参数无效
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                                          ^
/usr/include/absl/strings/cord.h:1045:46: 错误：‘string_view’不是‘absl’的成员
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1045:46: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/strings/cord.h:1045:58: 错误：模板第 1 个参数无效
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                                          ^
/usr/include/absl/strings/cord.h:1045:32: 错误：‘absl::Nonnull’不是一个类型
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                ^~~~~~~
/usr/include/absl/strings/cord.h:1045:39: 错误：expected ‘,’ or ‘...’ before ‘<’ token
 1045 |                          absl::Nonnull<absl::string_view*> fragment);
      |                                       ^
/usr/include/absl/strings/cord.h:1050:36: 错误：‘string_view’不是‘absl’的成员
 1050 |       absl::FunctionRef<void(absl::string_view)> callback);
      |                                    ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1050:48: 错误：模板第 1 个参数无效
 1050 |       absl::FunctionRef<void(absl::string_view)> callback);
      |                                                ^
/usr/include/absl/strings/cord.h:1057:29: 错误：‘absl::string_view’尚未声明
 1057 |   int CompareSlowPath(absl::string_view rhs, size_t compared_size,
      |                             ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1061:25: 错误：‘absl::string_view’尚未声明
 1061 |   bool EqualsImpl(absl::string_view rhs, size_t size_to_compare) const;
      |                         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1068:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1068 |   static absl::string_view GetFirstChunk(const Cord& c);
      |                ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1069:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1069 |   static absl::string_view GetFirstChunk(absl::string_view sv);
      |                ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1084:28: 错误：‘absl::string_view’尚未声明
 1084 |   void AppendPrecise(absl::string_view src, MethodIdentifier method);
      |                            ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1085:29: 错误：‘absl::string_view’尚未声明
 1085 |   void PrependPrecise(absl::string_view src, MethodIdentifier method);
      |                             ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1092:27: 错误：‘absl::string_view’尚未声明
 1092 |   void PrependArray(absl::string_view src, MethodIdentifier method);
      |                           ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1114:48: 错误：‘absl::string_view’尚未声明
 1114 |   CharIterator FindImpl(CharIterator it, absl::string_view needle) const;
      |                                                ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In function ‘void absl::lts_20240722::AbslStringify(Sink&, const Cord&)’:
/usr/include/absl/strings/cord.h:790:16: 错误：‘string_view’不是‘absl’的成员
  790 |     for (absl::string_view chunk : cord.Chunks()) {
      |                ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:793:3: 错误：expected primary-expression before ‘}’ token
  793 |   }
      |   ^
/usr/include/absl/strings/cord.h:793:3: 错误：expected ‘;’ before ‘}’ token
/usr/include/absl/strings/cord.h:793:3: 错误：expected primary-expression before ‘}’ token
/usr/include/absl/strings/cord.h:793:3: 错误：expected ‘)’ before ‘}’ token
/usr/include/absl/strings/cord.h:790:9: 附注：to match this ‘(’
  790 |     for (absl::string_view chunk : cord.Chunks()) {
      |         ^
/usr/include/absl/strings/cord.h:793:3: 错误：expected primary-expression before ‘}’ token
  793 |   }
      |   ^
/usr/include/absl/strings/cord.h: In function ‘H absl::lts_20240722::AbslHashValue(H, const Cord&)’:
/usr/include/absl/strings/cord.h:820:11: 错误：‘optional’不是‘absl’的成员
  820 |     absl::optional<absl::string_view> maybe_flat = c.TryFlat();
      |           ^~~~~~~~
/usr/include/absl/strings/cord.h:820:26: 错误：‘string_view’不是‘absl’的成员
  820 |     absl::optional<absl::string_view> maybe_flat = c.TryFlat();
      |                          ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:820:39: 错误：‘maybe_flat’在此作用域中尚未声明
  820 |     absl::optional<absl::string_view> maybe_flat = c.TryFlat();
      |                                       ^~~~~~~~~~
/usr/include/absl/strings/cord.h:820:54: 错误：‘const class absl::lts_20240722::Cord’ has no member named ‘TryFlat’
  820 |     absl::optional<absl::string_view> maybe_flat = c.TryFlat();
      |                                                      ^~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘H absl::lts_20240722::Cord::HashFragmented(H) const’:
/usr/include/absl/strings/cord.h:1102:49: 错误：‘absl::string_view’尚未声明
 1102 |     ForEachChunk([&combiner, &hash_state](absl::string_view chunk) {
      |                                                 ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: 在 lambda 函数中:
/usr/include/absl/strings/cord.h:1103:69: 错误：对成员‘data’的请求出现在‘chunk’中，而后者具有非类类型‘int’
 1103 |       hash_state = combiner.add_buffer(std::move(hash_state), chunk.data(),
      |                                                                     ^~~~
/usr/include/absl/strings/cord.h:1104:46: 错误：对成员‘size’的请求出现在‘chunk’中，而后者具有非类类型‘int’
 1104 |                                        chunk.size());
      |                                              ^~~~
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1135:6: 错误：变量或字段‘InitializeCordRepExternal’声明为 void
 1135 | void InitializeCordRepExternal(absl::string_view data,
      |      ^~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1135:38: 错误：‘string_view’不是‘absl’的成员
 1135 | void InitializeCordRepExternal(absl::string_view data,
      |                                      ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1136:64: 错误：expected primary-expression before ‘rep’
 1136 |                                absl::Nonnull<CordRepExternal*> rep);
      |                                                                ^~~
/usr/include/absl/strings/cord.h:1142:46: 错误：‘string_view’不是‘absl’的成员
 1142 | absl::Nonnull<CordRep*> NewExternalRep(absl::string_view data,
      |                                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1143:48: 错误：expected primary-expression before ‘&&’ token
 1143 |                                        Releaser&& releaser) {
      |                                                ^~
/usr/include/absl/strings/cord.h:1143:51: 错误：‘releaser’ was not declared in this scope; did you mean ‘Releaser’?
 1143 |                                        Releaser&& releaser) {
      |                                                   ^~~~~~~~
      |                                                   Releaser
/usr/include/absl/strings/cord.h:1143:59: 错误：expression list treated as compound expression in initializer [-fpermissive]
 1143 |                                        Releaser&& releaser) {
      |                                                           ^
/usr/include/absl/strings/cord.h:1143:60: 错误：expected ‘;’ before ‘{’ token
 1143 |                                        Releaser&& releaser) {
      |                                                            ^~
      |                                                            ;
/usr/include/absl/strings/cord.h:1156:11: 错误：‘absl::lts_20240722::cord_internal::CordRep* absl::lts_20240722::cord_internal::NewExternalRep’ redeclared as different kind of entity
 1156 |     absl::string_view data, void (&releaser)(absl::string_view)) {
      |           ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1142:25: 附注：previous declaration ‘template<class Releaser> absl::lts_20240722::cord_internal::CordRep* absl::lts_20240722::cord_internal::NewExternalRep<Releaser>’
 1142 | absl::Nonnull<CordRep*> NewExternalRep(absl::string_view data,
      |                         ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1156:11: 错误：‘string_view’不是‘absl’的成员
 1156 |     absl::string_view data, void (&releaser)(absl::string_view)) {
      |           ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1156:36: 错误：‘releaser’在此作用域中尚未声明
 1156 |     absl::string_view data, void (&releaser)(absl::string_view)) {
      |                                    ^~~~~~~~
/usr/include/absl/strings/cord.h:1156:52: 错误：‘string_view’不是‘absl’的成员
 1156 |     absl::string_view data, void (&releaser)(absl::string_view)) {
      |                                                    ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1163:6: 错误：‘template<class Releaser> absl::lts_20240722::Cord absl::lts_20240722::MakeCordFromExternal’ 重定义
 1163 | Cord MakeCordFromExternal(absl::string_view data, Releaser&& releaser) {
      |      ^~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:107:6: 附注：‘template<class Releaser> absl::lts_20240722::Cord absl::lts_20240722::MakeCordFromExternal<Releaser>’已在此定义过
  107 | Cord MakeCordFromExternal(absl::string_view, Releaser&&);
      |      ^~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1163:33: 错误：‘string_view’不是‘absl’的成员
 1163 | Cord MakeCordFromExternal(absl::string_view data, Releaser&& releaser) {
      |                                 ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1163:59: 错误：expected primary-expression before ‘&&’ token
 1163 | Cord MakeCordFromExternal(absl::string_view data, Releaser&& releaser) {
      |                                                           ^~
/usr/include/absl/strings/cord.h:1163:62: 错误：‘releaser’ was not declared in this scope; did you mean ‘Releaser’?
 1163 | Cord MakeCordFromExternal(absl::string_view data, Releaser&& releaser) {
      |                                                              ^~~~~~~~
      |                                                              Releaser
/usr/include/absl/strings/cord.h:1178:11: 错误：‘constexpr const int absl::lts_20240722::Cord::InlineRep::InlineRep’ is not a static data member of ‘class absl::lts_20240722::Cord::InlineRep’
 1178 | constexpr Cord::InlineRep::InlineRep(absl::string_view sv,
      |           ^~~~
/usr/include/absl/strings/cord.h:1178:44: 错误：‘string_view’不是‘absl’的成员
 1178 | constexpr Cord::InlineRep::InlineRep(absl::string_view sv,
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1179:63: 错误：expected primary-expression before ‘rep’
 1179 |                                      absl::Nullable<CordRep*> rep)
      |                                                               ^~~
/usr/include/absl/strings/cord.h:1179:66: 错误：expression list treated as compound expression in initializer [-fpermissive]
 1179 |                                      absl::Nullable<CordRep*> rep)
      |                                                                  ^
/usr/include/absl/strings/cord.h:1338:8: 错误：‘int absl::lts_20240722::Cord::Cord’ is not a static data member of ‘class absl::lts_20240722::Cord’
 1338 | inline Cord::Cord(absl::string_view src)
      |        ^~~~
/usr/include/absl/strings/cord.h:1338:25: 错误：‘string_view’不是‘absl’的成员
 1338 | inline Cord::Cord(absl::string_view src)
      |                         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘absl::lts_20240722::Cord& absl::lts_20240722::Cord::operator=(T&&)’:
/usr/include/absl/strings/cord.h:1358:28: 错误：‘string_view’不是‘absl’的成员
 1358 |     return operator=(absl::string_view(src));
      |                            ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1405:14: 错误：‘optional’ in namespace ‘absl’ does not name a template type
 1405 | inline absl::optional<absl::string_view> Cord::TryFlat() const
      |              ^~~~~~~~
/usr/include/absl/strings/cord.h:1418:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1418 | inline absl::string_view Cord::Flatten() ABSL_ATTRIBUTE_LIFETIME_BOUND {
      |              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1431:13: 错误：变量或字段‘Append’声明为 void
 1431 | inline void Cord::Append(absl::string_view src) {
      |             ^~~~
/usr/include/absl/strings/cord.h:1431:32: 错误：‘string_view’不是‘absl’的成员
 1431 | inline void Cord::Append(absl::string_view src) {
      |                                ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1435:13: 错误：变量或字段‘Prepend’声明为 void
 1435 | inline void Cord::Prepend(absl::string_view src) {
      |             ^~~~
/usr/include/absl/strings/cord.h:1435:33: 错误：‘string_view’不是‘absl’的成员
 1435 | inline void Cord::Prepend(absl::string_view src) {
      |                                 ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘void absl::lts_20240722::Cord::Append(absl::lts_20240722::CordBuffer)’:
/usr/include/absl/strings/cord.h:1442:9: 错误：‘string_view’不是‘absl’的成员
 1442 |   absl::string_view short_value;
      |         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1443:42: 错误：‘short_value’在此作用域中尚未声明
 1443 |   if (CordRep* rep = buffer.ConsumeValue(short_value)) {
      |                                          ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘void absl::lts_20240722::Cord::Prepend(absl::lts_20240722::CordBuffer)’:
/usr/include/absl/strings/cord.h:1453:9: 错误：‘string_view’不是‘absl’的成员
 1453 |   absl::string_view short_value;
      |         ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1454:42: 错误：‘short_value’在此作用域中尚未声明
 1454 |   if (CordRep* rep = buffer.ConsumeValue(short_value)) {
      |                                          ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1495:13: 错误：‘bool absl::lts_20240722::Cord::StartsWith’ is not a static data member of ‘class absl::lts_20240722::Cord’
 1495 | inline bool Cord::StartsWith(absl::string_view rhs) const {
      |             ^~~~
/usr/include/absl/strings/cord.h:1495:36: 错误：‘string_view’不是‘absl’的成员
 1495 | inline bool Cord::StartsWith(absl::string_view rhs) const {
      |                                    ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘void absl::lts_20240722::Cord::ChunkIterator::InitTree(absl::lts_20240722::Nonnull<absl::lts_20240722::cord_internal::CordRep*>)’:
/usr/include/absl/strings/cord.h:1513:5: 错误：‘current_chunk_’在此作用域中尚未声明
 1513 |     current_chunk_ = btree_reader_.Init(tree->btree());
      |     ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1513:36: 错误：‘using absl::lts_20240722::Cord::ChunkIterator::CordRepBtreeReader = class absl::lts_20240722::cord_internal::CordRepBtreeReader’ {aka ‘class absl::lts_20240722::cord_internal::CordRepBtreeReader’} has no member named ‘Init’
 1513 |     current_chunk_ = btree_reader_.Init(tree->btree());
      |                                    ^~~~
/usr/include/absl/strings/cord.h:1516:5: 错误：‘current_chunk_’在此作用域中尚未声明
 1516 |     current_chunk_ = cord_internal::EdgeData(tree);
      |     ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1516:37: 错误：‘EdgeData’不是‘absl::lts_20240722::cord_internal’的成员
 1516 |     current_chunk_ = cord_internal::EdgeData(tree);
      |                                     ^~~~~~~~
/usr/include/absl/strings/cord.h: In constructor ‘absl::lts_20240722::Cord::ChunkIterator::ChunkIterator(absl::lts_20240722::Nonnull<const absl::lts_20240722::Cord*>)’:
/usr/include/absl/strings/cord.h:1532:7: 错误：‘current_chunk_’在此作用域中尚未声明
 1532 |       current_chunk_ = {};
      |       ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1536:5: 错误：‘current_chunk_’在此作用域中尚未声明
 1536 |     current_chunk_ = {cord->contents_.data(), bytes_remaining_};
      |     ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘absl::lts_20240722::Cord::ChunkIterator& absl::lts_20240722::Cord::ChunkIterator::AdvanceBtree()’:
/usr/include/absl/strings/cord.h:1541:3: 错误：‘current_chunk_’在此作用域中尚未声明
 1541 |   current_chunk_ = btree_reader_.Next();
      |   ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1541:34: 错误：‘using absl::lts_20240722::Cord::ChunkIterator::CordRepBtreeReader = class absl::lts_20240722::cord_internal::CordRepBtreeReader’ {aka ‘class absl::lts_20240722::cord_internal::CordRepBtreeReader’} has no member named ‘Next’
 1541 |   current_chunk_ = btree_reader_.Next();
      |                                  ^~~~
/usr/include/absl/strings/cord.h: In member function ‘void absl::lts_20240722::Cord::ChunkIterator::AdvanceBytesBtree(size_t)’:
/usr/include/absl/strings/cord.h:1549:14: 错误：‘current_chunk_’在此作用域中尚未声明
 1549 |     if (n == current_chunk_.size()) {
      |              ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h:1550:38: 错误：‘using absl::lts_20240722::Cord::ChunkIterator::CordRepBtreeReader = class absl::lts_20240722::cord_internal::CordRepBtreeReader’ {aka ‘class absl::lts_20240722::cord_internal::CordRepBtreeReader’} has no member named ‘Next’
 1550 |       current_chunk_ = btree_reader_.Next();
      |                                      ^~~~
/usr/include/absl/strings/cord.h:1553:38: 错误：‘using absl::lts_20240722::Cord::ChunkIterator::CordRepBtreeReader = class absl::lts_20240722::cord_internal::CordRepBtreeReader’ {aka ‘class absl::lts_20240722::cord_internal::CordRepBtreeReader’} has no member named ‘Seek’
 1553 |       current_chunk_ = btree_reader_.Seek(offset);
      |                                      ^~~~
/usr/include/absl/strings/cord.h:1556:5: 错误：‘current_chunk_’在此作用域中尚未声明
 1556 |     current_chunk_ = {};
      |     ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘absl::lts_20240722::Cord::ChunkIterator& absl::lts_20240722::Cord::ChunkIterator::operator++()’:
/usr/include/absl/strings/cord.h:1564:23: 错误：‘current_chunk_’在此作用域中尚未声明
 1564 |   bytes_remaining_ -= current_chunk_.size();
      |                       ^~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1590:29: 错误：‘reference’ in ‘class absl::lts_20240722::Cord::ChunkIterator’ does not name a type
 1590 | inline Cord::ChunkIterator::reference Cord::ChunkIterator::operator*() const {
      |                             ^~~~~~~~~
/usr/include/absl/strings/cord.h:1595:29: 错误：‘pointer’ in ‘class absl::lts_20240722::Cord::ChunkIterator’ does not name a type
 1595 | inline Cord::ChunkIterator::pointer Cord::ChunkIterator::operator->() const {
      |                             ^~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘void absl::lts_20240722::Cord::ChunkIterator::RemoveChunkPrefix(size_t)’:
/usr/include/absl/strings/cord.h:1602:3: 错误：‘current_chunk_’在此作用域中尚未声明
 1602 |   current_chunk_.remove_prefix(n);
      |   ^~~~~~~~~~~~~~
In file included from /usr/include/absl/base/macros.h:36,
                 from /usr/include/absl/strings/string_view.h:43:
/usr/include/absl/strings/cord.h: In member function ‘void absl::lts_20240722::Cord::ChunkIterator::AdvanceBytes(size_t)’:
/usr/include/absl/strings/cord.h:1608:7: 错误：‘current_chunk_’在此作用域中尚未声明
 1608 |   if (ABSL_PREDICT_TRUE(n < current_chunk_.size())) {
      |       ^~~~~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘absl::lts_20240722::Cord::CharIterator& absl::lts_20240722::Cord::CharIterator::operator++()’:
/usr/include/absl/strings/cord.h:1636:7: 错误：‘->’的基操作数具有非指针类型‘absl::lts_20240722::Cord::ChunkIterator’
 1636 |   if (ABSL_PREDICT_TRUE(chunk_iterator_->size() > 1)) {
      |       ^~~~~~~~~~~~~~~~~
/usr/include/absl/strings/cord.h: In member function ‘const char& absl::lts_20240722::Cord::CharIterator::operator*() const’:
/usr/include/absl/strings/cord.h:1659:26: 错误：‘->’的基操作数具有非指针类型‘const absl::lts_20240722::Cord::ChunkIterator’
 1659 |   return *chunk_iterator_->data();
      |                          ^~
/usr/include/absl/strings/cord.h: In member function ‘const char* absl::lts_20240722::Cord::CharIterator::operator->() const’:
/usr/include/absl/strings/cord.h:1663:25: 错误：‘->’的基操作数具有非指针类型‘const absl::lts_20240722::Cord::ChunkIterator’
 1663 |   return chunk_iterator_->data();
      |                         ^~
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1677:14: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1677 | inline absl::string_view Cord::ChunkRemaining(const CharIterator& it) {
      |              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1698:34: 错误：‘string_view’不是‘absl’的成员
 1698 |     absl::FunctionRef<void(absl::string_view)> callback) const {
      |                                  ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1698:46: 错误：模板第 1 个参数无效
 1698 |     absl::FunctionRef<void(absl::string_view)> callback) const {
      |                                              ^
/usr/include/absl/strings/cord.h: In member function ‘void absl::lts_20240722::Cord::ForEachChunk(int) const’:
/usr/include/absl/strings/cord.h:1701:20: 错误：‘string_view’不是‘absl’的成员
 1701 |     callback(absl::string_view(contents_.data(), contents_.size()));
      |                    ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1701:67: 错误：‘callback’ cannot be used as a function
 1701 |     callback(absl::string_view(contents_.data(), contents_.size()));
      |                                                                   ^
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1729:47: 错误：‘absl::string_view’尚未声明
 1729 | inline bool operator==(const Cord& lhs, absl::string_view rhs) {
      |                                               ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In function ‘bool absl::lts_20240722::operator==(const Cord&, int)’:
/usr/include/absl/strings/cord.h:1731:25: 错误：对成员‘size’的请求出现在‘rhs’中，而后者具有非类类型‘int’
 1731 |   size_t rhs_size = rhs.size();
      |                         ^~~~
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1736:13: 错误：‘operator==’没有声明为一个函数
 1736 | inline bool operator==(absl::string_view x, const Cord& y) { return y == x; }
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1736:30: 错误：‘string_view’不是‘absl’的成员
 1736 | inline bool operator==(absl::string_view x, const Cord& y) { return y == x; }
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1736:45: 错误：expected primary-expression before ‘const’
 1736 | inline bool operator==(absl::string_view x, const Cord& y) { return y == x; }
      |                                             ^~~~~
/usr/include/absl/strings/cord.h:1737:45: 错误：‘absl::string_view’尚未声明
 1737 | inline bool operator!=(const Cord& x, absl::string_view y) { return !(x == y); }
      |                                             ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1738:13: 错误：‘operator!=’没有声明为一个函数
 1738 | inline bool operator!=(absl::string_view x, const Cord& y) { return !(x == y); }
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1738:30: 错误：‘string_view’不是‘absl’的成员
 1738 | inline bool operator!=(absl::string_view x, const Cord& y) { return !(x == y); }
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1738:45: 错误：expected primary-expression before ‘const’
 1738 | inline bool operator!=(absl::string_view x, const Cord& y) { return !(x == y); }
      |                                             ^~~~~
/usr/include/absl/strings/cord.h:1739:44: 错误：‘absl::string_view’尚未声明
 1739 | inline bool operator<(const Cord& x, absl::string_view y) {
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1742:13: 错误：‘operator<’没有声明为一个函数
 1742 | inline bool operator<(absl::string_view x, const Cord& y) {
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1742:29: 错误：‘string_view’不是‘absl’的成员
 1742 | inline bool operator<(absl::string_view x, const Cord& y) {
      |                             ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1742:44: 错误：expected primary-expression before ‘const’
 1742 | inline bool operator<(absl::string_view x, const Cord& y) {
      |                                            ^~~~~
/usr/include/absl/strings/cord.h:1745:44: 错误：‘absl::string_view’尚未声明
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In function ‘bool absl::lts_20240722::operator>(const Cord&, int)’:
/usr/include/absl/strings/cord.h:1745:70: 错误：no match for ‘operator<’ (operand types are ‘int’ and ‘const absl::lts_20240722::Cord’)
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                                                    ~ ^ ~
      |                                                                    |   |
      |                                                                    int const absl::lts_20240722::Cord
In file included from /usr/include/absl/log/log_entry.h:36:
/usr/include/absl/types/span.h:547:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator<(Span<T>, Span<T>)’
  547 | bool operator<(Span<T> a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:547:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1745:72: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                                                        ^
/usr/include/absl/types/span.h:551:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator<(Span<const T>, Span<T>)’
  551 | bool operator<(Span<const T> a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:551:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1745:72: 附注：  mismatched types ‘absl::lts_20240722::Span<const T>’ and ‘int’
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                                                        ^
/usr/include/absl/types/span.h:555:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator<(Span<T>, Span<const T>)’
  555 | bool operator<(Span<T> a, Span<const T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:555:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1745:72: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                                                        ^
/usr/include/absl/types/span.h:561:6: 附注：备选： ‘template<class T, class U, class> bool absl::lts_20240722::operator<(const U&, Span<T>)’
  561 | bool operator<(const U& a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:561:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1745:72: 附注：  ‘absl::lts_20240722::Cord’ is not derived from ‘absl::lts_20240722::Span<T>’
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                                                        ^
/usr/include/absl/types/span.h:567:6: 附注：备选： ‘template<class T, class U, class> bool absl::lts_20240722::operator<(Span<T>, const U&)’
  567 | bool operator<(Span<T> a, const U& b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:567:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1745:72: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                                                        ^
/usr/include/absl/container/inlined_vector.h:964:6: 附注：备选： ‘template<class T, long unsigned int N, class A> bool absl::lts_20240722::operator<(const InlinedVector<T, N, A>&, const InlinedVector<T, N, A>&)’
  964 | bool operator<(const absl::InlinedVector<T, N, A>& a,
      |      ^~~~~~~~
/usr/include/absl/container/inlined_vector.h:964:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1745:72: 附注：  mismatched types ‘const absl::lts_20240722::InlinedVector<T, N, A>’ and ‘int’
 1745 | inline bool operator>(const Cord& x, absl::string_view y) { return y < x; }
      |                                                                        ^
In file included from /usr/include/absl/log/internal/nullstream.h:36:
/usr/include/absl/base/log_severity.h:176:1: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(LogSeverity, LogSeverityAtLeast)’
  176 | COMPOP(>, <, LogSeverityAtLeast)
      | ^~~~~~
/usr/include/absl/base/log_severity.h:176:1: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::LogSeverity’
  176 | COMPOP(>, <, LogSeverityAtLeast)
      | ^~~~~~
/usr/include/absl/base/log_severity.h:178:1: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(LogSeverityAtMost, LogSeverity)’
  178 | COMPOP(<, >, LogSeverityAtMost)
      | ^~~~~~
/usr/include/absl/base/log_severity.h:178:1: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::LogSeverityAtMost’
  178 | COMPOP(<, >, LogSeverityAtMost)
      | ^~~~~~
/usr/include/absl/time/time.h:1745:46: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(Duration, Duration)’
 1745 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Duration lhs,
      |                                              ^~~~~~~~
/usr/include/absl/time/time.h:1745:65: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::Duration’
 1745 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Duration lhs,
      |                                                        ~~~~~~~~~^~~
/usr/include/absl/time/time.h:880:46: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(Time, Time)’
  880 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Time lhs, Time rhs) {
      |                                              ^~~~~~~~
/usr/include/absl/time/time.h:880:61: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::Time’
  880 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Time lhs, Time rhs) {
      |                                                        ~~~~~^~~
In file included from /usr/include/absl/strings/internal/str_format/arg.h:35:
/usr/include/absl/numeric/int128.h:810:16: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(uint128, uint128)’
  810 | constexpr bool operator<(uint128 lhs, uint128 rhs) {
      |                ^~~~~~~~
/usr/include/absl/numeric/int128.h:810:47: 附注：  no known conversion for argument 2 from ‘const absl::lts_20240722::Cord’ to ‘absl::lts_20240722::uint128’
  810 | constexpr bool operator<(uint128 lhs, uint128 rhs) {
      |                                       ~~~~~~~~^~~
In file included from /usr/include/absl/numeric/int128.h:1182:
/usr/include/absl/numeric/int128_have_intrinsic.inc:207:16: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(int128, int128)’
  207 | constexpr bool operator<(int128 lhs, int128 rhs) {
      |                ^~~~~~~~
/usr/include/absl/numeric/int128_have_intrinsic.inc:207:45: 附注：  no known conversion for argument 2 from ‘const absl::lts_20240722::Cord’ to ‘absl::lts_20240722::int128’
  207 | constexpr bool operator<(int128 lhs, int128 rhs) {
      |                                      ~~~~~~~^~~
/usr/include/absl/strings/cord.h:1716:13: 附注：备选： ‘bool absl::lts_20240722::operator<(const Cord&, const Cord&)’
 1716 | inline bool operator<(const Cord& x, const Cord& y) { return x.Compare(y) < 0; }
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1716:35: 附注：  no known conversion for argument 1 from ‘int’ to ‘const absl::lts_20240722::Cord&’
 1716 | inline bool operator<(const Cord& x, const Cord& y) { return x.Compare(y) < 0; }
      |                       ~~~~~~~~~~~~^
/usr/include/absl/strings/cord.h:1739:13: 附注：备选： ‘bool absl::lts_20240722::operator<(const Cord&, int)’
 1739 | inline bool operator<(const Cord& x, absl::string_view y) {
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1739:35: 附注：  no known conversion for argument 1 from ‘int’ to ‘const absl::lts_20240722::Cord&’
 1739 | inline bool operator<(const Cord& x, absl::string_view y) {
      |                       ~~~~~~~~~~~~^
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1746:13: 错误：‘operator>’没有声明为一个函数
 1746 | inline bool operator>(absl::string_view x, const Cord& y) { return y < x; }
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1746:29: 错误：‘string_view’不是‘absl’的成员
 1746 | inline bool operator>(absl::string_view x, const Cord& y) { return y < x; }
      |                             ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1746:44: 错误：expected primary-expression before ‘const’
 1746 | inline bool operator>(absl::string_view x, const Cord& y) { return y < x; }
      |                                            ^~~~~
/usr/include/absl/strings/cord.h:1747:45: 错误：‘absl::string_view’尚未声明
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                             ^~~~~~~~~~~
/usr/include/absl/strings/cord.h: In function ‘bool absl::lts_20240722::operator<=(const Cord&, int)’:
/usr/include/absl/strings/cord.h:1747:73: 错误：no match for ‘operator<’ (operand types are ‘int’ and ‘const absl::lts_20240722::Cord’)
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                                                       ~ ^ ~
      |                                                                       |   |
      |                                                                       int const absl::lts_20240722::Cord
/usr/include/absl/types/span.h:547:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator<(Span<T>, Span<T>)’
  547 | bool operator<(Span<T> a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:547:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1747:75: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                                                           ^
/usr/include/absl/types/span.h:551:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator<(Span<const T>, Span<T>)’
  551 | bool operator<(Span<const T> a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:551:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1747:75: 附注：  mismatched types ‘absl::lts_20240722::Span<const T>’ and ‘int’
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                                                           ^
/usr/include/absl/types/span.h:555:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator<(Span<T>, Span<const T>)’
  555 | bool operator<(Span<T> a, Span<const T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:555:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1747:75: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                                                           ^
/usr/include/absl/types/span.h:561:6: 附注：备选： ‘template<class T, class U, class> bool absl::lts_20240722::operator<(const U&, Span<T>)’
  561 | bool operator<(const U& a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:561:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1747:75: 附注：  ‘absl::lts_20240722::Cord’ is not derived from ‘absl::lts_20240722::Span<T>’
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                                                           ^
/usr/include/absl/types/span.h:567:6: 附注：备选： ‘template<class T, class U, class> bool absl::lts_20240722::operator<(Span<T>, const U&)’
  567 | bool operator<(Span<T> a, const U& b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:567:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1747:75: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                                                           ^
/usr/include/absl/container/inlined_vector.h:964:6: 附注：备选： ‘template<class T, long unsigned int N, class A> bool absl::lts_20240722::operator<(const InlinedVector<T, N, A>&, const InlinedVector<T, N, A>&)’
  964 | bool operator<(const absl::InlinedVector<T, N, A>& a,
      |      ^~~~~~~~
/usr/include/absl/container/inlined_vector.h:964:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/strings/cord.h:1747:75: 附注：  mismatched types ‘const absl::lts_20240722::InlinedVector<T, N, A>’ and ‘int’
 1747 | inline bool operator<=(const Cord& x, absl::string_view y) { return !(y < x); }
      |                                                                           ^
/usr/include/absl/base/log_severity.h:176:1: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(LogSeverity, LogSeverityAtLeast)’
  176 | COMPOP(>, <, LogSeverityAtLeast)
      | ^~~~~~
/usr/include/absl/base/log_severity.h:176:1: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::LogSeverity’
  176 | COMPOP(>, <, LogSeverityAtLeast)
      | ^~~~~~
/usr/include/absl/base/log_severity.h:178:1: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(LogSeverityAtMost, LogSeverity)’
  178 | COMPOP(<, >, LogSeverityAtMost)
      | ^~~~~~
/usr/include/absl/base/log_severity.h:178:1: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::LogSeverityAtMost’
  178 | COMPOP(<, >, LogSeverityAtMost)
      | ^~~~~~
/usr/include/absl/time/time.h:1745:46: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(Duration, Duration)’
 1745 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Duration lhs,
      |                                              ^~~~~~~~
/usr/include/absl/time/time.h:1745:65: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::Duration’
 1745 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Duration lhs,
      |                                                        ~~~~~~~~~^~~
/usr/include/absl/time/time.h:880:46: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(Time, Time)’
  880 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Time lhs, Time rhs) {
      |                                              ^~~~~~~~
/usr/include/absl/time/time.h:880:61: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::Time’
  880 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator<(Time lhs, Time rhs) {
      |                                                        ~~~~~^~~
/usr/include/absl/numeric/int128.h:810:16: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(uint128, uint128)’
  810 | constexpr bool operator<(uint128 lhs, uint128 rhs) {
      |                ^~~~~~~~
/usr/include/absl/numeric/int128.h:810:47: 附注：  no known conversion for argument 2 from ‘const absl::lts_20240722::Cord’ to ‘absl::lts_20240722::uint128’
  810 | constexpr bool operator<(uint128 lhs, uint128 rhs) {
      |                                       ~~~~~~~~^~~
/usr/include/absl/numeric/int128_have_intrinsic.inc:207:16: 附注：备选： ‘constexpr bool absl::lts_20240722::operator<(int128, int128)’
  207 | constexpr bool operator<(int128 lhs, int128 rhs) {
      |                ^~~~~~~~
/usr/include/absl/numeric/int128_have_intrinsic.inc:207:45: 附注：  no known conversion for argument 2 from ‘const absl::lts_20240722::Cord’ to ‘absl::lts_20240722::int128’
  207 | constexpr bool operator<(int128 lhs, int128 rhs) {
      |                                      ~~~~~~~^~~
/usr/include/absl/strings/cord.h:1716:13: 附注：备选： ‘bool absl::lts_20240722::operator<(const Cord&, const Cord&)’
 1716 | inline bool operator<(const Cord& x, const Cord& y) { return x.Compare(y) < 0; }
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1716:35: 附注：  no known conversion for argument 1 from ‘int’ to ‘const absl::lts_20240722::Cord&’
 1716 | inline bool operator<(const Cord& x, const Cord& y) { return x.Compare(y) < 0; }
      |                       ~~~~~~~~~~~~^
/usr/include/absl/strings/cord.h:1739:13: 附注：备选： ‘bool absl::lts_20240722::operator<(const Cord&, int)’
 1739 | inline bool operator<(const Cord& x, absl::string_view y) {
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1739:35: 附注：  no known conversion for argument 1 from ‘int’ to ‘const absl::lts_20240722::Cord&’
 1739 | inline bool operator<(const Cord& x, absl::string_view y) {
      |                       ~~~~~~~~~~~~^
/usr/include/absl/strings/cord.h: 在全局域：
/usr/include/absl/strings/cord.h:1748:13: 错误：‘operator<=’没有声明为一个函数
 1748 | inline bool operator<=(absl::string_view x, const Cord& y) { return !(y < x); }
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1748:30: 错误：‘string_view’不是‘absl’的成员
 1748 | inline bool operator<=(absl::string_view x, const Cord& y) { return !(y < x); }
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1748:45: 错误：expected primary-expression before ‘const’
 1748 | inline bool operator<=(absl::string_view x, const Cord& y) { return !(y < x); }
      |                                             ^~~~~
/usr/include/absl/strings/cord.h:1749:45: 错误：‘absl::string_view’尚未声明
 1749 | inline bool operator>=(const Cord& x, absl::string_view y) { return !(x < y); }
      |                                             ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1750:13: 错误：‘operator>=’没有声明为一个函数
 1750 | inline bool operator>=(absl::string_view x, const Cord& y) { return !(x < y); }
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1750:30: 错误：‘string_view’不是‘absl’的成员
 1750 | inline bool operator>=(absl::string_view x, const Cord& y) { return !(x < y); }
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/cord.h:1750:45: 错误：expected primary-expression before ‘const’
 1750 | inline bool operator>=(absl::string_view x, const Cord& y) { return !(x < y); }
      |                                             ^~~~~
In file included from /usr/include/google/protobuf/io/coded_stream.h:114:
/usr/include/google/protobuf/port.h:202:14: 错误：‘optional’ in namespace ‘absl’ does not name a template type
  202 | inline absl::optional<absl::string_view> RttiTypeName() {
      |              ^~~~~~~~
/usr/include/google/protobuf/port.h:351:46: 错误：expected ‘)’ before ‘name’
  351 |   explicit RealDebugCounter(absl::string_view name) { Register(name); }
      |                            ~                 ^~~~~
      |                                              )
/usr/include/google/protobuf/port.h:357:23: 错误：‘absl::string_view’尚未声明
  357 |   void Register(absl::string_view name);
      |                       ^~~~~~~~~~~
/usr/include/google/protobuf/io/coded_stream.h:866:51: 错误：‘absl::string_view’尚未声明
  866 |   uint8_t* WriteStringOutline(uint32_t num, absl::string_view s, uint8_t* ptr);
      |                                                   ^~~~~~~~~~~
/usr/include/google/protobuf/io/coded_stream.h: In member function ‘std::ptrdiff_t google::protobuf::io::EpsCopyOutputStream::GetSize(uint8_t*) const’:
/usr/include/google/protobuf/io/coded_stream.h:828:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  828 |     ABSL_DCHECK(ptr <= end_ + kSlopBytes);  // NOLINT
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/io/coded_stream.h: In member function ‘uint8_t* google::protobuf::io::EpsCopyOutputStream::WriteTag(uint32_t, uint32_t, uint8_t*)’:
/usr/include/google/protobuf/io/coded_stream.h:849:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  849 |     ABSL_DCHECK(ptr < end_);  // NOLINT
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/io/coded_stream.h: In member function ‘bool google::protobuf::io::CodedOutputStream::HadError()’:
/usr/include/google/protobuf/io/coded_stream.h:1058:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 1058 |     ABSL_DCHECK(cur_);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/arena_align.h: In function ‘google::protobuf::internal::ArenaAlign google::protobuf::internal::ArenaAlignAs(size_t)’:
/usr/include/google/protobuf/arena_align.h:159:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  159 |   ABSL_DCHECK(absl::has_single_bit(align)) << "Invalid alignment " << align;
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/string_block.h: In static member function ‘static size_t google::protobuf::internal::StringBlock::Delete(google::protobuf::internal::StringBlock*)’:
/usr/include/google/protobuf/string_block.h:147:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  147 |   ABSL_DCHECK(block != nullptr);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/serial_arena.h: In member function ‘bool google::protobuf::internal::SerialArena::MaybeAllocateAligned(size_t, void**)’:
/usr/include/google/protobuf/serial_arena.h:203:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  203 |     ABSL_DCHECK(internal::ArenaAlignDefault::IsAligned(n));
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/serial_arena.h: In static member function ‘static const char* google::protobuf::internal::SerialArena::MaybePrefetchImpl(ptrdiff_t, const char*, const char*, const char*)’:
/usr/include/google/protobuf/serial_arena.h:291:7: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  291 |       ABSL_DCHECK(prefetch_ptr != nullptr);
      |       ^~~~~~~~~~~
      |       |
      |       const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/serial_arena.h: In member function ‘void google::protobuf::internal::SerialArena::MaybePrefetchData(const char*)’:
/usr/include/google/protobuf/serial_arena.h:301:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  301 |     ABSL_DCHECK(static_cast<const void*>(prefetch_ptr_) == nullptr ||
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/serial_arena.h: In member function ‘void google::protobuf::internal::SerialArena::MaybePrefetchCleanup()’:
/usr/include/google/protobuf/serial_arena.h:308:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  308 |     ABSL_DCHECK(static_cast<const void*>(cleanup_list_.prefetch_ptr_) ==
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h: In member function ‘std::string* google::protobuf::internal::TaggedStringPtr::TagAs(Type, std::string*)’:
/usr/include/google/protobuf/arenastring.h:197:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  197 |     ABSL_DCHECK(p != nullptr);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /home/kbrd/libopenshot/build/src/objdetectdata.pb.h:22:
/usr/include/google/protobuf/arenastring.h: 在全局域：
/usr/include/google/protobuf/arenastring.h:298:18: 错误：‘absl::string_view’尚未声明
  298 |   void Set(absl::string_view value, Arena* arena);
      |                  ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h:305:23: 错误：‘absl::string_view’尚未声明
  305 |   void SetBytes(absl::string_view value, Arena* arena);
      |                       ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h: In constructor ‘google::protobuf::internal::ArenaStringPtr::ArenaStringPtr(google::protobuf::Arena*)’:
/usr/include/google/protobuf/arenastring.h:244:17: 错误：‘string_view’不是‘absl’的成员
  244 |       Set(absl::string_view(""), arena);
      |                 ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h: In constructor ‘google::protobuf::internal::ArenaStringPtr::ArenaStringPtr(google::protobuf::Arena*, const google::protobuf::internal::LazyString&)’:
/usr/include/google/protobuf/arenastring.h:255:17: 错误：‘string_view’不是‘absl’的成员
  255 |       Set(absl::string_view(default_value.get()), arena);
      |                 ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h: In member function ‘void google::protobuf::internal::ArenaStringPtr::Set(const char*, google::protobuf::Arena*)’:
/usr/include/google/protobuf/arenastring.h:469:13: 错误：‘string_view’不是‘absl’的成员
  469 |   Set(absl::string_view{s}, arena);
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h: In member function ‘void google::protobuf::internal::ArenaStringPtr::Set(const char*, size_t, google::protobuf::Arena*)’:
/usr/include/google/protobuf/arenastring.h:473:13: 错误：‘string_view’不是‘absl’的成员
  473 |   Set(absl::string_view{s, n}, arena);
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h: 在全局域：
/usr/include/google/protobuf/arenastring.h:476:13: 错误：变量或字段‘SetBytes’声明为 void
  476 | inline void ArenaStringPtr::SetBytes(absl::string_view value, Arena* arena) {
      |             ^~~~~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h:476:44: 错误：‘string_view’不是‘absl’的成员
  476 | inline void ArenaStringPtr::SetBytes(absl::string_view value, Arena* arena) {
      |                                            ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h:476:68: 错误：expected primary-expression before ‘*’ token
  476 | inline void ArenaStringPtr::SetBytes(absl::string_view value, Arena* arena) {
      |                                                                    ^
/usr/include/google/protobuf/arenastring.h:476:70: 错误：‘arena’ was not declared in this scope; did you mean ‘Arena’?
  476 | inline void ArenaStringPtr::SetBytes(absl::string_view value, Arena* arena) {
      |                                                                      ^~~~~
      |                                                                      Arena
/usr/include/google/protobuf/arenastring.h: In member function ‘void google::protobuf::internal::ArenaStringPtr::SetBytes(const void*, size_t, google::protobuf::Arena*)’:
/usr/include/google/protobuf/arenastring.h:498:13: 错误：‘string_view’不是‘absl’的成员
  498 |   Set(absl::string_view{static_cast<const char*>(p), n}, arena);
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h: In member function ‘std::string* google::protobuf::internal::ArenaStringPtr::UnsafeMutablePointer()’:
/usr/include/google/protobuf/arenastring.h:530:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  530 |   ABSL_DCHECK(tagged_ptr_.IsMutable());
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/arenastring.h:531:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  531 |   ABSL_DCHECK(tagged_ptr_.Get() != nullptr);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /usr/include/google/protobuf/generated_message_tctable_decl.h:22,
                 from /home/kbrd/libopenshot/build/src/objdetectdata.pb.h:23:
/usr/include/google/protobuf/message_lite.h: 在全局域：
/usr/include/google/protobuf/message_lite.h:346:59: 错误：‘absl::string_view’尚未声明
  346 |   ABSL_ATTRIBUTE_REINITIALIZES bool ParseFromString(absl::string_view data);
      |                                                           ^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:350:13: 错误：‘absl::string_view’尚未声明
  350 |       absl::string_view data);
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:380:30: 错误：‘absl::string_view’尚未声明
  380 |   bool MergeFromString(absl::string_view data);
      |                              ^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:594:24: 错误：expected identifier before ‘*’ token
  594 |     absl::string_view (*get_type_name)(const ClassData* data);
      |                        ^
/usr/include/google/protobuf/message_lite.h:594:61: 错误：‘string_view’声明为返回一个函数的函数
  594 |     absl::string_view (*get_type_name)(const ClassData* data);
      |                                                             ^
/usr/include/google/protobuf/message_lite.h: In member function ‘const google::protobuf::internal::TcParseTableBase* google::protobuf::MessageLite::GetTcParseTable() const’:
/usr/include/google/protobuf/message_lite.h:578:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  578 |     ABSL_DCHECK(data != nullptr);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:582:7: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  582 |       ABSL_DCHECK(!data->is_lite);
      |       ^~~~~~~~~~~
      |       |
      |       const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h: In member function ‘const google::protobuf::MessageLite::ClassDataFull& google::protobuf::MessageLite::ClassData::full() const’:
/usr/include/google/protobuf/message_lite.h:685:7: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  685 |       ABSL_DCHECK(!is_lite);
      |       ^~~~~~~~~~~
      |       |
      |       const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h: 在全局域：
/usr/include/google/protobuf/message_lite.h:891:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  891 |   absl::string_view name() const;
      |         ^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:933:26: 错误：‘string_view’不是‘absl’的成员
  933 | bool MergeFromImpl(absl::string_view input, MessageLite* msg,
      |                          ^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:933:56: 错误：expected primary-expression before ‘*’ token
  933 | bool MergeFromImpl(absl::string_view input, MessageLite* msg,
      |                                                        ^
/usr/include/google/protobuf/message_lite.h:933:58: 错误：‘msg’在此作用域中尚未声明
  933 | bool MergeFromImpl(absl::string_view input, MessageLite* msg,
      |                                                          ^~~
/usr/include/google/protobuf/message_lite.h:934:20: 错误：expected primary-expression before ‘const’
  934 |                    const internal::TcParseTableBase* tc_table,
      |                    ^~~~~
/usr/include/google/protobuf/message_lite.h:935:44: 错误：expected primary-expression before ‘parse_flags’
  935 |                    MessageLite::ParseFlags parse_flags);
      |                                            ^~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:935:55: 错误：expression list treated as compound expression in initializer [-fpermissive]
  935 |                    MessageLite::ParseFlags parse_flags);
      |                                                       ^
/usr/include/google/protobuf/message_lite.h:936:75: 错误：expected ‘;’ before ‘(’ token
  936 | extern template PROTOBUF_EXPORT_TEMPLATE_DECLARE bool MergeFromImpl<false>(
      |                                                                           ^
      |                                                                           ;
/usr/include/google/protobuf/message_lite.h:940:74: 错误：expected ‘;’ before ‘(’ token
  940 | extern template PROTOBUF_EXPORT_TEMPLATE_DECLARE bool MergeFromImpl<true>(
      |                                                                          ^
      |                                                                          ;
/usr/include/google/protobuf/message_lite.h:948:55: 错误：‘template<bool alias> bool google::protobuf::internal::MergeFromImpl(google::protobuf::io::ZeroCopyInputStream*, google::protobuf::MessageLite*, const TcParseTableBase*, google::protobuf::MessageLite::ParseFlags)’ conflicts with a previous declaration
  948 |                    MessageLite::ParseFlags parse_flags);
      |                                                       ^
/usr/include/google/protobuf/message_lite.h:933:6: 附注：previous declaration ‘template<bool alias> bool google::protobuf::internal::MergeFromImpl<alias>’
  933 | bool MergeFromImpl(absl::string_view input, MessageLite* msg,
      |      ^~~~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:949:55: 错误：‘template<bool alias> bool google::protobuf::internal::MergeFromImpl<alias>’不是一个函数模板
  949 | extern template PROTOBUF_EXPORT_TEMPLATE_DECLARE bool MergeFromImpl<false>(
      |                                                       ^~~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:953:55: 错误：‘template<bool alias> bool google::protobuf::internal::MergeFromImpl<alias>’不是一个函数模板
  953 | extern template PROTOBUF_EXPORT_TEMPLATE_DECLARE bool MergeFromImpl<true>(
      |                                                       ^~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:966:55: 错误：‘template<bool alias> bool google::protobuf::internal::MergeFromImpl(BoundedZCIS, google::protobuf::MessageLite*, const TcParseTableBase*, google::protobuf::MessageLite::ParseFlags)’ conflicts with a previous declaration
  966 |                    MessageLite::ParseFlags parse_flags);
      |                                                       ^
/usr/include/google/protobuf/message_lite.h:933:6: 附注：previous declaration ‘template<bool alias> bool google::protobuf::internal::MergeFromImpl<alias>’
  933 | bool MergeFromImpl(absl::string_view input, MessageLite* msg,
      |      ^~~~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:967:55: 错误：‘template<bool alias> bool google::protobuf::internal::MergeFromImpl<alias>’不是一个函数模板
  967 | extern template PROTOBUF_EXPORT_TEMPLATE_DECLARE bool MergeFromImpl<false>(
      |                                                       ^~~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:971:55: 错误：‘template<bool alias> bool google::protobuf::internal::MergeFromImpl<alias>’不是一个函数模板
  971 | extern template PROTOBUF_EXPORT_TEMPLATE_DECLARE bool MergeFromImpl<true>(
      |                                                       ^~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h:982:55: 错误：‘template<bool alias, class T> bool google::protobuf::internal::MergeFromImpl(const SourceWrapper<T>&, google::protobuf::MessageLite*, const TcParseTableBase*, google::protobuf::MessageLite::ParseFlags)’ conflicts with a previous declaration
  982 |                    MessageLite::ParseFlags parse_flags) {
      |                                                       ^
/usr/include/google/protobuf/message_lite.h:933:6: 附注：previous declaration ‘template<bool alias> bool google::protobuf::internal::MergeFromImpl<alias>’
  933 | bool MergeFromImpl(absl::string_view input, MessageLite* msg,
      |      ^~~~~~~~~~~~~
/usr/include/google/protobuf/message_lite.h: In function ‘void google::protobuf::internal::AssertDownCast(const google::protobuf::MessageLite&, const google::protobuf::MessageLite&)’:
/usr/include/google/protobuf/message_lite.h:1031:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 1031 |   ABSL_DCHECK(TypeId::Get(from) == TypeId::Get(to))
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /usr/include/absl/log/absl_vlog_is_on.h:61,
                 from /usr/include/absl/log/internal/log_impl.h:18,
                 from /usr/include/absl/log/absl_log.h:36,
                 from /usr/include/google/protobuf/parse_context.h:19,
                 from /usr/include/google/protobuf/generated_message_tctable_decl.h:23:
/usr/include/absl/log/internal/vlog_config.h: 在全局域：
/usr/include/absl/log/internal/vlog_config.h:128:21: 错误：‘string_view’不是‘absl’的成员
  128 | int VLogLevel(absl::string_view file);
      |                     ^~~~~~~~~~~
/usr/include/absl/log/internal/vlog_config.h:140:6: 错误：变量或字段‘UpdateVModule’声明为 void
  140 | void UpdateVModule(absl::string_view vmodule);
      |      ^~~~~~~~~~~~~
/usr/include/absl/log/internal/vlog_config.h:140:26: 错误：‘string_view’不是‘absl’的成员
  140 | void UpdateVModule(absl::string_view vmodule);
      |                          ^~~~~~~~~~~
/usr/include/absl/log/internal/vlog_config.h:150:26: 错误：‘string_view’不是‘absl’的成员
  150 | int PrependVModule(absl::string_view module_pattern, int log_level);
      |                          ^~~~~~~~~~~
/usr/include/absl/log/internal/vlog_config.h:150:54: 错误：expected primary-expression before ‘int’
  150 | int PrependVModule(absl::string_view module_pattern, int log_level);
      |                                                      ^~~
/usr/include/absl/log/internal/vlog_config.h:150:67: 错误：expression list treated as compound expression in initializer [-fpermissive]
  150 | int PrependVModule(absl::string_view module_pattern, int log_level);
      |                                                                   ^
In file included from /usr/include/google/protobuf/parse_context.h:27:
/usr/include/google/protobuf/inlined_string_field.h:113:18: 错误：‘absl::string_view’尚未声明
  113 |   void Set(absl::string_view value, Arena* arena, bool donated,
      |                  ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:132:23: 错误：‘absl::string_view’尚未声明
  132 |   void SetBytes(absl::string_view value, Arena* arena, bool donated,
      |                       ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:150:48: 错误：‘absl::string_view’尚未声明
  150 |   PROTOBUF_NDEBUG_INLINE void SetNoArena(absl::string_view value);
      |                                                ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:418:13: 错误：变量或字段‘SetNoArena’声明为 void
  418 | inline void InlinedStringField::SetNoArena(absl::string_view value) {
      |             ^~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:418:50: 错误：‘string_view’不是‘absl’的成员
  418 | inline void InlinedStringField::SetNoArena(absl::string_view value) {
      |                                                  ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:448:13: 错误：变量或字段‘Set’声明为 void
  448 | inline void InlinedStringField::Set(absl::string_view value, Arena* arena,
      |             ^~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:448:43: 错误：‘string_view’不是‘absl’的成员
  448 | inline void InlinedStringField::Set(absl::string_view value, Arena* arena,
      |                                           ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:448:67: 错误：expected primary-expression before ‘*’ token
  448 | inline void InlinedStringField::Set(absl::string_view value, Arena* arena,
      |                                                                   ^
/usr/include/google/protobuf/inlined_string_field.h:448:69: 错误：‘arena’ was not declared in this scope; did you mean ‘Arena’?
  448 | inline void InlinedStringField::Set(absl::string_view value, Arena* arena,
      |                                                                     ^~~~~
      |                                                                     Arena
/usr/include/google/protobuf/inlined_string_field.h:449:37: 错误：expected primary-expression before ‘bool’
  449 |                                     bool donated, uint32_t* /*donating_states*/,
      |                                     ^~~~
/usr/include/google/protobuf/inlined_string_field.h:449:59: 错误：expected primary-expression before ‘*’ token
  449 |                                     bool donated, uint32_t* /*donating_states*/,
      |                                                           ^
/usr/include/google/protobuf/inlined_string_field.h:449:80: 错误：expected primary-expression before ‘,’ token
  449 |                                     bool donated, uint32_t* /*donating_states*/,
      |                                                                                ^
/usr/include/google/protobuf/inlined_string_field.h:450:54: 错误：expected primary-expression before ‘,’ token
  450 |                                     uint32_t /*mask*/, MessageLite* /*msg*/) {
      |                                                      ^
/usr/include/google/protobuf/inlined_string_field.h:450:67: 错误：expected primary-expression before ‘*’ token
  450 |                                     uint32_t /*mask*/, MessageLite* /*msg*/) {
      |                                                                   ^
/usr/include/google/protobuf/inlined_string_field.h:450:76: 错误：expected primary-expression before ‘)’ token
  450 |                                     uint32_t /*mask*/, MessageLite* /*msg*/) {
      |                                                                            ^
/usr/include/google/protobuf/inlined_string_field.h: In member function ‘void google::protobuf::internal::InlinedStringField::Set(const char*, google::protobuf::Arena*, bool, uint32_t*, uint32_t, google::protobuf::MessageLite*)’:
/usr/include/google/protobuf/inlined_string_field.h:459:13: 错误：‘string_view’不是‘absl’的成员
  459 |   Set(absl::string_view(str), arena, donated, donating_states, mask, msg);
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h: In member function ‘void google::protobuf::internal::InlinedStringField::Set(const char*, size_t, google::protobuf::Arena*, bool, uint32_t*, uint32_t, google::protobuf::MessageLite*)’:
/usr/include/google/protobuf/inlined_string_field.h:466:13: 错误：‘string_view’不是‘absl’的成员
  466 |   Set(absl::string_view{str, size}, arena, donated, donating_states, mask, msg);
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h: 在全局域：
/usr/include/google/protobuf/inlined_string_field.h:469:13: 错误：变量或字段‘SetBytes’声明为 void
  469 | inline void InlinedStringField::SetBytes(absl::string_view value, Arena* arena,
      |             ^~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:469:48: 错误：‘string_view’不是‘absl’的成员
  469 | inline void InlinedStringField::SetBytes(absl::string_view value, Arena* arena,
      |                                                ^~~~~~~~~~~
/usr/include/google/protobuf/inlined_string_field.h:469:72: 错误：expected primary-expression before ‘*’ token
  469 | inline void InlinedStringField::SetBytes(absl::string_view value, Arena* arena,
      |                                                                        ^
/usr/include/google/protobuf/inlined_string_field.h:469:74: 错误：‘arena’ was not declared in this scope; did you mean ‘Arena’?
  469 | inline void InlinedStringField::SetBytes(absl::string_view value, Arena* arena,
      |                                                                          ^~~~~
      |                                                                          Arena
/usr/include/google/protobuf/inlined_string_field.h:470:42: 错误：expected primary-expression before ‘bool’
  470 |                                          bool donated,
      |                                          ^~~~
/usr/include/google/protobuf/inlined_string_field.h:471:50: 错误：expected primary-expression before ‘*’ token
  471 |                                          uint32_t* donating_states,
      |                                                  ^
/usr/include/google/protobuf/inlined_string_field.h:471:52: 错误：‘donating_states’ was not declared in this scope; did you mean ‘InitDonatingStates’?
  471 |                                          uint32_t* donating_states,
      |                                                    ^~~~~~~~~~~~~~~
      |                                                    InitDonatingStates
/usr/include/google/protobuf/inlined_string_field.h:472:51: 错误：expected primary-expression before ‘mask’
  472 |                                          uint32_t mask, MessageLite* msg) {
      |                                                   ^~~~
/usr/include/google/protobuf/inlined_string_field.h:472:68: 错误：expected primary-expression before ‘*’ token
  472 |                                          uint32_t mask, MessageLite* msg) {
      |                                                                    ^
/usr/include/google/protobuf/inlined_string_field.h:472:70: 错误：‘msg’在此作用域中尚未声明
  472 |                                          uint32_t mask, MessageLite* msg) {
      |                                                                      ^~~
In file included from /usr/include/google/protobuf/repeated_field.h:41,
                 from /usr/include/google/protobuf/parse_context.h:32:
/usr/include/google/protobuf/generated_enum_util.h:43:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
   43 |   absl::string_view name;
      |         ^~~~~~~~~~~
/usr/include/google/protobuf/generated_enum_util.h:49:44: 错误：‘absl::string_view’尚未声明
   49 |                                      absl::string_view name, int* value);
      |                                            ^~~~~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h: In member function ‘void google::protobuf::internal::RepeatedPtrFieldBase::InternalSwap(google::protobuf::internal::RepeatedPtrFieldBase*)’:
/usr/include/google/protobuf/repeated_ptr_field.h:280:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  280 |     ABSL_DCHECK(this != rhs);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h: In member function ‘void google::protobuf::internal::RepeatedPtrFieldBase::AddAllocatedForParse(void*)’:
/usr/include/google/protobuf/repeated_ptr_field.h:294:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  294 |     ABSL_DCHECK(PrepareForParse());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h: In member function ‘google::protobuf::internal::RepeatedPtrFieldBase::Rep* google::protobuf::internal::RepeatedPtrFieldBase::rep()’:
/usr/include/google/protobuf/repeated_ptr_field.h:645:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  645 |     ABSL_DCHECK(!using_sso());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /usr/include/google/protobuf/parse_context.h:33:
/usr/include/google/protobuf/wire_format_lite.h: 在全局域：
/usr/include/google/protobuf/wire_format_lite.h:716:41: 错误：‘absl::string_view’尚未声明
  716 |   static inline size_t StringSize(absl::string_view value);
      |                                         ^~~~~~~~~~~
/usr/include/google/protobuf/wire_format_lite.h:717:40: 错误：‘absl::string_view’尚未声明
  717 |   static inline size_t BytesSize(absl::string_view value);
      |                                        ^~~~~~~~~~~
/usr/include/google/protobuf/wire_format_lite.h:1815:54: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1815 | inline size_t WireFormatLite::StringSize(const absl::string_view value) {
      |                                                      ^~~~~~~~~~~
/usr/include/google/protobuf/wire_format_lite.h: In static member function ‘static size_t google::protobuf::internal::WireFormatLite::StringSize(int)’:
/usr/include/google/protobuf/wire_format_lite.h:1819:36: 错误：对成员‘size’的请求出现在‘value’中，而后者具有非类类型‘const int’
 1819 |   return LengthDelimitedSize(value.size());
      |                                    ^~~~
/usr/include/google/protobuf/wire_format_lite.h: 在全局域：
/usr/include/google/protobuf/wire_format_lite.h:1821:53: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1821 | inline size_t WireFormatLite::BytesSize(const absl::string_view value) {
      |                                                     ^~~~~~~~~~~
/usr/include/google/protobuf/wire_format_lite.h: In static member function ‘static size_t google::protobuf::internal::WireFormatLite::BytesSize(int)’:
/usr/include/google/protobuf/wire_format_lite.h:1822:36: 错误：对成员‘size’的请求出现在‘value’中，而后者具有非类类型‘const int’
 1822 |   return LengthDelimitedSize(value.size());
      |                                    ^~~~
/usr/include/google/protobuf/parse_context.h: 在全局域：
/usr/include/google/protobuf/parse_context.h:51:63: 错误：‘absl::string_view’尚未声明
   51 | PROTOBUF_EXPORT void WriteLengthDelimited(uint32_t num, absl::string_view val,
      |                                                               ^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h:55:54: 错误：‘absl::string_view’尚未声明
   55 | inline void WriteLengthDelimited(uint32_t num, absl::string_view val,
      |                                                      ^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h:279:30: 错误：‘absl::string_view’尚未声明
  279 |   const char* InitFrom(absl::string_view flat) {
      |                              ^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h: In member function ‘void google::protobuf::internal::EpsCopyInputStream::BackUp(const char*)’:
/usr/include/google/protobuf/parse_context.h:103:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  103 |     ABSL_DCHECK(ptr <= buffer_end_ + kSlopBytes);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h: In member function ‘google::protobuf::internal::EpsCopyInputStream::LimitToken google::protobuf::internal::EpsCopyInputStream::PushLimit(const char*, int)’:
/usr/include/google/protobuf/parse_context.h:151:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  151 |     ABSL_DCHECK(limit >= 0 && limit <= INT_MAX - kSlopBytes);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h: In member function ‘const char* google::protobuf::internal::EpsCopyInputStream::ReadCord(const char*, int, absl::lts_20240722::Cord*)’:
/usr/include/google/protobuf/parse_context.h:209:21: 错误：‘string_view’不是‘absl’的成员
  209 |       *cord = absl::string_view(ptr, size);
      |                     ^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h: In member function ‘bool google::protobuf::internal::EpsCopyInputStream::DoneWithCheck(const char**, int)’:
/usr/include/google/protobuf/parse_context.h:263:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  263 |     ABSL_DCHECK(*ptr);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h: In member function ‘const char* google::protobuf::internal::EpsCopyInputStream::InitFrom(int)’:
/usr/include/google/protobuf/parse_context.h:281:14: 错误：对成员‘size’的请求出现在‘flat’中，而后者具有非类类型‘int’
  281 |     if (flat.size() > kSlopBytes) {
      |              ^~~~
/usr/include/google/protobuf/parse_context.h:283:39: 错误：对成员‘data’的请求出现在‘flat’中，而后者具有非类类型‘int’
  283 |       limit_end_ = buffer_end_ = flat.data() + flat.size() - kSlopBytes;
      |                                       ^~~~
/usr/include/google/protobuf/parse_context.h:283:53: 错误：对成员‘size’的请求出现在‘flat’中，而后者具有非类类型‘int’
  283 |       limit_end_ = buffer_end_ = flat.data() + flat.size() - kSlopBytes;
      |                                                     ^~~~
/usr/include/google/protobuf/parse_context.h:286:19: 错误：对成员‘data’的请求出现在‘flat’中，而后者具有非类类型‘int’
  286 |       return flat.data();
      |                   ^~~~
/usr/include/google/protobuf/parse_context.h:288:17: 错误：对成员‘empty’的请求出现在‘flat’中，而后者具有非类类型‘int’
  288 |       if (!flat.empty()) {
      |                 ^~~~~
/usr/include/google/protobuf/parse_context.h:289:41: 错误：对成员‘data’的请求出现在‘flat’中，而后者具有非类类型‘int’
  289 |         std::memcpy(patch_buffer_, flat.data(), flat.size());
      |                                         ^~~~
/usr/include/google/protobuf/parse_context.h:289:54: 错误：对成员‘size’的请求出现在‘flat’中，而后者具有非类类型‘int’
  289 |         std::memcpy(patch_buffer_, flat.data(), flat.size());
      |                                                      ^~~~
/usr/include/google/protobuf/parse_context.h:292:55: 错误：对成员‘size’的请求出现在‘flat’中，而后者具有非类类型‘int’
  292 |       limit_end_ = buffer_end_ = patch_buffer_ + flat.size();
      |                                                       ^~~~
/usr/include/google/protobuf/parse_context.h:295:59: 错误：对成员‘data’的请求出现在‘flat’中，而后者具有非类类型‘int’
  295 |         aliasing_ = reinterpret_cast<std::uintptr_t>(flat.data()) -
      |                                                           ^~~~
/usr/include/google/protobuf/parse_context.h: 在全局域：
/usr/include/google/protobuf/parse_context.h:1252:23: 错误：‘string_view’不是‘absl’的成员
 1252 | bool VerifyUTF8(absl::string_view s, const char* field_name);
      |                       ^~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h:1252:38: 错误：expected primary-expression before ‘const’
 1252 | bool VerifyUTF8(absl::string_view s, const char* field_name);
      |                                      ^~~~~
/usr/include/google/protobuf/parse_context.h:1252:60: 错误：expression list treated as compound expression in initializer [-fpermissive]
 1252 | bool VerifyUTF8(absl::string_view s, const char* field_name);
      |                                                            ^
/usr/include/google/protobuf/parse_context.h:1254:68: 错误：‘bool google::protobuf::internal::VerifyUTF8(const std::string*, const char*)’ redeclared as different kind of entity
 1254 | inline bool VerifyUTF8(const std::string* s, const char* field_name) {
      |                                                                    ^
/usr/include/google/protobuf/parse_context.h:1252:6: 附注：previous declaration ‘bool google::protobuf::internal::VerifyUTF8’
 1252 | bool VerifyUTF8(absl::string_view s, const char* field_name);
      |      ^~~~~~~~~~
/usr/include/google/protobuf/parse_context.h: In function ‘bool google::protobuf::internal::VerifyUTF8(const std::string*, const char*)’:
/usr/include/google/protobuf/parse_context.h:1255:20: 错误：‘google::protobuf::internal::VerifyUTF8’ cannot be used as a function
 1255 |   return VerifyUTF8(*s, field_name);
      |          ~~~~~~~~~~^~~~~~~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_decl.h: In member function ‘bool google::protobuf::internal::MapTypeCard::is_signed() const’:
/usr/include/google/protobuf/generated_message_tctable_decl.h:168:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  168 |     ABSL_DCHECK(cpp_type() == CppType::k32 || cpp_type() == CppType::k64);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_decl.h: In member function ‘bool google::protobuf::internal::MapTypeCard::is_zigzag() const’:
/usr/include/google/protobuf/generated_message_tctable_decl.h:173:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  173 |     ABSL_DCHECK(wiretype() == WireFormatLite::WIRETYPE_VARINT);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_decl.h:174:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  174 |     ABSL_DCHECK(cpp_type() == CppType::k32 || cpp_type() == CppType::k64);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_decl.h: In member function ‘bool google::protobuf::internal::MapTypeCard::is_utf8() const’:
/usr/include/google/protobuf/generated_message_tctable_decl.h:178:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  178 |     ABSL_DCHECK(wiretype() == WireFormatLite::WIRETYPE_LENGTH_DELIMITED);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_decl.h:179:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  179 |     ABSL_DCHECK(cpp_type() == CppType::kString);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /usr/include/google/protobuf/generated_message_util.h:34,
                 from /home/kbrd/libopenshot/build/src/objdetectdata.pb.h:24:
/usr/include/google/protobuf/any.h: 在全局域：
/usr/include/google/protobuf/any.h:35:30: 错误：‘string_view’不是‘absl’的成员
   35 | std::string GetTypeUrl(absl::string_view message_name,
      |                              ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:36:30: 错误：‘string_view’不是‘absl’的成员
   36 |                        absl::string_view type_url_prefix);
      |                              ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:69:23: 错误：‘absl::string_view’尚未声明
   69 |                 absl::string_view type_url_prefix) {
      |                       ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:75:23: 错误：‘absl::string_view’尚未声明
   75 |                 absl::string_view type_url_prefix);
      |                       ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:98:31: 错误：‘absl::string_view’尚未声明
   98 |                         absl::string_view type_url_prefix,
      |                               ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:99:31: 错误：‘absl::string_view’尚未声明
   99 |                         absl::string_view type_name);
      |                               ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:100:31: 错误：‘absl::string_view’尚未声明
  100 |   bool InternalUnpackTo(absl::string_view type_name,
      |                               ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:102:25: 错误：‘absl::string_view’尚未声明
  102 |   bool InternalIs(absl::string_view type_name) const;
      |                         ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:115:28: 错误：‘string_view’不是‘absl’的成员
  115 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* full_type_name);
      |                            ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:115:61: 错误：expected primary-expression before ‘*’ token
  115 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* full_type_name);
      |                                                             ^
/usr/include/google/protobuf/any.h:115:63: 错误：‘full_type_name’在此作用域中尚未声明
  115 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* full_type_name);
      |                                                               ^~~~~~~~~~~~~~
/usr/include/google/protobuf/any.h:115:77: 错误：expression list treated as compound expression in initializer [-fpermissive]
  115 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* full_type_name);
      |                                                                             ^
/usr/include/google/protobuf/any.h:122:6: 错误：‘bool google::protobuf::internal::ParseAnyTypeUrl’ 重定义
  122 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* url_prefix,
      |      ^~~~~~~~~~~~~~~
/usr/include/google/protobuf/any.h:115:6: 附注：‘bool google::protobuf::internal::ParseAnyTypeUrl’ previously defined here
  115 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* full_type_name);
      |      ^~~~~~~~~~~~~~~
/usr/include/google/protobuf/any.h:122:28: 错误：‘string_view’不是‘absl’的成员
  122 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* url_prefix,
      |                            ^~~~~~~~~~~
/usr/include/google/protobuf/any.h:122:61: 错误：expected primary-expression before ‘*’ token
  122 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* url_prefix,
      |                                                             ^
/usr/include/google/protobuf/any.h:122:63: 错误：‘url_prefix’在此作用域中尚未声明
  122 | bool ParseAnyTypeUrl(absl::string_view type_url, std::string* url_prefix,
      |                                                               ^~~~~~~~~~
/usr/include/google/protobuf/any.h:123:33: 错误：expected primary-expression before ‘*’ token
  123 |                      std::string* full_type_name);
      |                                 ^
/usr/include/google/protobuf/any.h:123:35: 错误：‘full_type_name’在此作用域中尚未声明
  123 |                      std::string* full_type_name);
      |                                   ^~~~~~~~~~~~~~
/usr/include/google/protobuf/generated_message_util.h:359:53: 错误：‘absl::string_view’尚未声明
  359 | inline void AssignToString(std::string& dest, absl::string_view value,
      |                                                     ^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_util.h: In function ‘void google::protobuf::internal::AssignToString(std::string&, int, BytesTag)’:
/usr/include/google/protobuf/generated_message_util.h:361:21: 错误：对成员‘data’的请求出现在‘value’中，而后者具有非类类型‘int’
  361 |   dest.assign(value.data(), value.size());
      |                     ^~~~
/usr/include/google/protobuf/generated_message_util.h:361:35: 错误：对成员‘size’的请求出现在‘value’中，而后者具有非类类型‘int’
  361 |   dest.assign(value.data(), value.size());
      |                                   ^~~~
In file included from /usr/include/absl/container/internal/btree.h:63,
                 from /usr/include/absl/container/btree_map.h:59,
                 from /usr/include/google/protobuf/descriptor.h:45,
                 from /usr/include/google/protobuf/generated_message_reflection.h:25,
                 from /home/kbrd/libopenshot/build/src/objdetectdata.pb.h:26:
/usr/include/absl/container/internal/common.h: 在全局域：
/usr/include/absl/container/internal/common.h:113:9: 错误：‘optional’ in namespace ‘absl’ does not name a template type
  113 |   absl::optional<allocator_type> alloc_ = {};
      |         ^~~~~~~~
/usr/include/absl/container/internal/common.h: In member function ‘absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>& absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::operator=(absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>&&)’:
/usr/include/absl/container/internal/common.h:67:7: 错误：‘alloc_’ was not declared in this scope; did you mean ‘alloc’?
   67 |       alloc_ = other.alloc_;
      |       ^~~~~~
      |       alloc
/usr/include/absl/container/internal/common.h: In member function ‘bool absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::empty() const’:
/usr/include/absl/container/internal/common.h:74:41: 错误：‘alloc_’ was not declared in this scope; did you mean ‘alloc’?
   74 |   bool empty() const noexcept { return !alloc_; }
      |                                         ^~~~~~
      |                                         alloc
/usr/include/absl/container/internal/common.h: In member function ‘absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::allocator_type absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::get_allocator() const’:
/usr/include/absl/container/internal/common.h:76:50: 错误：‘alloc_’ was not declared in this scope; did you mean ‘alloc’?
   76 |   allocator_type get_allocator() const { return *alloc_; }
      |                                                  ^~~~~~
      |                                                  alloc
/usr/include/absl/container/internal/common.h: In constructor ‘absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::node_handle_base(transfer_tag_t, const allocator_type&, slot_type*)’:
/usr/include/absl/container/internal/common.h:83:9: 错误：类‘absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>’没有名为‘alloc_’的字段
   83 |       : alloc_(a) {
      |         ^~~~~~
/usr/include/absl/container/internal/common.h: In constructor ‘absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::node_handle_base(construct_tag_t, const allocator_type&, Args&& ...)’:
/usr/include/absl/container/internal/common.h:90:9: 错误：类‘absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>’没有名为‘alloc_’的字段
   90 |       : alloc_(a) {
      |         ^~~~~~
/usr/include/absl/container/internal/common.h: In member function ‘void absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::reset()’:
/usr/include/absl/container/internal/common.h:103:5: 错误：‘alloc_’ was not declared in this scope; did you mean ‘alloc’?
  103 |     alloc_ = absl::nullopt;
      |     ^~~~~~
      |     alloc
/usr/include/absl/container/internal/common.h:103:20: 错误：‘nullopt’不是‘absl’的成员
  103 |     alloc_ = absl::nullopt;
      |                    ^~~~~~~
/usr/include/absl/container/internal/common.h: In member function ‘absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::allocator_type* absl::lts_20240722::container_internal::node_handle_base<PolicyTraits, Alloc>::alloc()’:
/usr/include/absl/container/internal/common.h:110:52: 错误：‘alloc_’ was not declared in this scope; did you mean ‘alloc’?
  110 |   allocator_type* alloc() { return std::addressof(*alloc_); }
      |                                                    ^~~~~~
      |                                                    alloc
In file included from /usr/include/absl/strings/str_cat.h:109,
                 from /usr/include/absl/container/internal/layout.h:199,
                 from /usr/include/absl/container/internal/btree.h:67:
/usr/include/absl/strings/internal/stringify_sink.h: 在全局域：
/usr/include/absl/strings/internal/stringify_sink.h:32:15: 错误：‘string_view’未声明
   32 |   void Append(string_view v);
      |               ^~~~~~~~~~~
/usr/include/absl/strings/internal/stringify_sink.h:35:58: 错误：‘absl::string_view’尚未声明
   35 |   friend void AbslFormatFlush(StringifySink* sink, absl::string_view v) {
      |                                                          ^~~~~~~~~~~
/usr/include/absl/strings/internal/stringify_sink.h:41:10: 错误：‘string_view’不是一个类型名
   41 |   friend string_view ExtractStringification(StringifySink& sink, const T& v);
      |          ^~~~~~~~~~~
/usr/include/absl/strings/internal/stringify_sink.h:47:1: 错误：‘string_view’不是一个类型名
   47 | string_view ExtractStringification(StringifySink& sink, const T& v) {
      | ^~~~~~~~~~~
In file included from /usr/include/absl/strings/str_cat.h:110:
/usr/include/absl/strings/numbers.h:63:44: 错误：‘string_view’不是‘absl’的成员
   63 | ABSL_MUST_USE_RESULT bool SimpleAtoi(absl::string_view str,
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:64:63: 错误：expected primary-expression before ‘out’
   64 |                                      absl::Nonnull<int_type*> out);
      |                                                               ^~~
/usr/include/absl/strings/numbers.h:64:66: 错误：expression list treated as compound expression in initializer [-fpermissive]
   64 |                                      absl::Nonnull<int_type*> out);
      |                                                                  ^
/usr/include/absl/strings/numbers.h:75:44: 错误：‘string_view’不是‘absl’的成员
   75 | ABSL_MUST_USE_RESULT bool SimpleAtof(absl::string_view str,
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:76:60: 错误：expected primary-expression before ‘out’
   76 |                                      absl::Nonnull<float*> out);
      |                                                            ^~~
/usr/include/absl/strings/numbers.h:76:63: 错误：expression list treated as compound expression in initializer [-fpermissive]
   76 |                                      absl::Nonnull<float*> out);
      |                                                               ^
/usr/include/absl/strings/numbers.h:87:44: 错误：‘string_view’不是‘absl’的成员
   87 | ABSL_MUST_USE_RESULT bool SimpleAtod(absl::string_view str,
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:88:61: 错误：expected primary-expression before ‘out’
   88 |                                      absl::Nonnull<double*> out);
      |                                                             ^~~
/usr/include/absl/strings/numbers.h:88:64: 错误：expression list treated as compound expression in initializer [-fpermissive]
   88 |                                      absl::Nonnull<double*> out);
      |                                                                ^
/usr/include/absl/strings/numbers.h:98:44: 错误：‘string_view’不是‘absl’的成员
   98 | ABSL_MUST_USE_RESULT bool SimpleAtob(absl::string_view str,
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:99:59: 错误：expected primary-expression before ‘out’
   99 |                                      absl::Nonnull<bool*> out);
      |                                                           ^~~
/usr/include/absl/strings/numbers.h:99:62: 错误：expression list treated as compound expression in initializer [-fpermissive]
   99 |                                      absl::Nonnull<bool*> out);
      |                                                              ^
/usr/include/absl/strings/numbers.h:112:47: 错误：‘string_view’不是‘absl’的成员
  112 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                                               ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:113:66: 错误：expected primary-expression before ‘out’
  113 |                                         absl::Nonnull<int_type*> out);
      |                                                                  ^~~
/usr/include/absl/strings/numbers.h:113:69: 错误：expression list treated as compound expression in initializer [-fpermissive]
  113 |                                         absl::Nonnull<int_type*> out);
      |                                                                     ^
/usr/include/absl/strings/numbers.h:117:11: 错误：‘bool absl::lts_20240722::SimpleHexAtoi’ redeclared as different kind of entity
  117 |     absl::string_view str, absl::Nonnull<absl::int128*> out);
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:112:27: 附注：previous declaration ‘template<class int_type> bool absl::lts_20240722::SimpleHexAtoi<int_type>’
  112 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                           ^~~~~~~~~~~~~
/usr/include/absl/strings/numbers.h:117:11: 错误：‘string_view’不是‘absl’的成员
  117 |     absl::string_view str, absl::Nonnull<absl::int128*> out);
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:117:57: 错误：expected primary-expression before ‘out’
  117 |     absl::string_view str, absl::Nonnull<absl::int128*> out);
      |                                                         ^~~
/usr/include/absl/strings/numbers.h:119:11: 错误：‘bool absl::lts_20240722::SimpleHexAtoi’ redeclared as different kind of entity
  119 |     absl::string_view str, absl::Nonnull<absl::uint128*> out);
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:112:27: 附注：previous declaration ‘template<class int_type> bool absl::lts_20240722::SimpleHexAtoi<int_type>’
  112 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                           ^~~~~~~~~~~~~
/usr/include/absl/strings/numbers.h:119:11: 错误：‘string_view’不是‘absl’的成员
  119 |     absl::string_view str, absl::Nonnull<absl::uint128*> out);
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:119:58: 错误：expected primary-expression before ‘out’
  119 |     absl::string_view str, absl::Nonnull<absl::uint128*> out);
      |                                                          ^~~
/usr/include/absl/strings/numbers.h:145:30: 错误：‘string_view’不是‘absl’的成员
  145 | bool safe_strto32_base(absl::string_view text, absl::Nonnull<int32_t*> value,
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:145:72: 错误：expected primary-expression before ‘value’
  145 | bool safe_strto32_base(absl::string_view text, absl::Nonnull<int32_t*> value,
      |                                                                        ^~~~~
/usr/include/absl/strings/numbers.h:146:24: 错误：expected primary-expression before ‘int’
  146 |                        int base);
      |                        ^~~
/usr/include/absl/strings/numbers.h:146:32: 错误：expression list treated as compound expression in initializer [-fpermissive]
  146 |                        int base);
      |                                ^
/usr/include/absl/strings/numbers.h:147:30: 错误：‘string_view’不是‘absl’的成员
  147 | bool safe_strto64_base(absl::string_view text, absl::Nonnull<int64_t*> value,
      |                              ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:147:72: 错误：expected primary-expression before ‘value’
  147 | bool safe_strto64_base(absl::string_view text, absl::Nonnull<int64_t*> value,
      |                                                                        ^~~~~
/usr/include/absl/strings/numbers.h:148:24: 错误：expected primary-expression before ‘int’
  148 |                        int base);
      |                        ^~~
/usr/include/absl/strings/numbers.h:148:32: 错误：expression list treated as compound expression in initializer [-fpermissive]
  148 |                        int base);
      |                                ^
/usr/include/absl/strings/numbers.h:149:31: 错误：‘string_view’不是‘absl’的成员
  149 | bool safe_strto128_base(absl::string_view text,
      |                               ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:150:54: 错误：expected primary-expression before ‘value’
  150 |                         absl::Nonnull<absl::int128*> value, int base);
      |                                                      ^~~~~
/usr/include/absl/strings/numbers.h:150:61: 错误：expected primary-expression before ‘int’
  150 |                         absl::Nonnull<absl::int128*> value, int base);
      |                                                             ^~~
/usr/include/absl/strings/numbers.h:150:69: 错误：expression list treated as compound expression in initializer [-fpermissive]
  150 |                         absl::Nonnull<absl::int128*> value, int base);
      |                                                                     ^
/usr/include/absl/strings/numbers.h:151:31: 错误：‘string_view’不是‘absl’的成员
  151 | bool safe_strtou32_base(absl::string_view text, absl::Nonnull<uint32_t*> value,
      |                               ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:151:74: 错误：expected primary-expression before ‘value’
  151 | bool safe_strtou32_base(absl::string_view text, absl::Nonnull<uint32_t*> value,
      |                                                                          ^~~~~
/usr/include/absl/strings/numbers.h:152:25: 错误：expected primary-expression before ‘int’
  152 |                         int base);
      |                         ^~~
/usr/include/absl/strings/numbers.h:152:33: 错误：expression list treated as compound expression in initializer [-fpermissive]
  152 |                         int base);
      |                                 ^
/usr/include/absl/strings/numbers.h:153:31: 错误：‘string_view’不是‘absl’的成员
  153 | bool safe_strtou64_base(absl::string_view text, absl::Nonnull<uint64_t*> value,
      |                               ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:153:74: 错误：expected primary-expression before ‘value’
  153 | bool safe_strtou64_base(absl::string_view text, absl::Nonnull<uint64_t*> value,
      |                                                                          ^~~~~
/usr/include/absl/strings/numbers.h:154:25: 错误：expected primary-expression before ‘int’
  154 |                         int base);
      |                         ^~~
/usr/include/absl/strings/numbers.h:154:33: 错误：expression list treated as compound expression in initializer [-fpermissive]
  154 |                         int base);
      |                                 ^
/usr/include/absl/strings/numbers.h:155:32: 错误：‘string_view’不是‘absl’的成员
  155 | bool safe_strtou128_base(absl::string_view text,
      |                                ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:156:56: 错误：expected primary-expression before ‘value’
  156 |                          absl::Nonnull<absl::uint128*> value, int base);
      |                                                        ^~~~~
/usr/include/absl/strings/numbers.h:156:63: 错误：expected primary-expression before ‘int’
  156 |                          absl::Nonnull<absl::uint128*> value, int base);
      |                                                               ^~~
/usr/include/absl/strings/numbers.h:156:71: 错误：expression list treated as compound expression in initializer [-fpermissive]
  156 |                          absl::Nonnull<absl::uint128*> value, int base);
      |                                                                       ^
/usr/include/absl/strings/numbers.h:213:50: 错误：‘string_view’不是‘absl’的成员
  213 | ABSL_MUST_USE_RESULT bool safe_strtoi_base(absl::string_view s,
      |                                                  ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:214:69: 错误：expected primary-expression before ‘out’
  214 |                                            absl::Nonnull<int_type*> out,
      |                                                                     ^~~
/usr/include/absl/strings/numbers.h:215:44: 错误：expected primary-expression before ‘int’
  215 |                                            int base) {
      |                                            ^~~
/usr/include/absl/strings/numbers.h:215:52: 错误：expression list treated as compound expression in initializer [-fpermissive]
  215 |                                            int base) {
      |                                                    ^
/usr/include/absl/strings/numbers.h:215:53: 错误：expected ‘;’ before ‘{’ token
  215 |                                            int base) {
      |                                                     ^~
      |                                                     ;
/usr/include/absl/strings/numbers.h:283:27: 错误：‘template<class int_type> bool absl::lts_20240722::SimpleAtoi’ 重定义
  283 | ABSL_MUST_USE_RESULT bool SimpleAtoi(absl::string_view str,
      |                           ^~~~~~~~~~
/usr/include/absl/strings/numbers.h:63:27: 附注：‘template<class int_type> bool absl::lts_20240722::SimpleAtoi<int_type>’已在此定义过
   63 | ABSL_MUST_USE_RESULT bool SimpleAtoi(absl::string_view str,
      |                           ^~~~~~~~~~
/usr/include/absl/strings/numbers.h:283:44: 错误：‘string_view’不是‘absl’的成员
  283 | ABSL_MUST_USE_RESULT bool SimpleAtoi(absl::string_view str,
      |                                            ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:284:63: 错误：expected primary-expression before ‘out’
  284 |                                      absl::Nonnull<int_type*> out) {
      |                                                               ^~~
/usr/include/absl/strings/numbers.h:288:51: 错误：‘bool absl::lts_20240722::SimpleAtoi’ redeclared as different kind of entity
  288 | ABSL_MUST_USE_RESULT inline bool SimpleAtoi(absl::string_view str,
      |                                                   ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:63:27: 附注：previous declaration ‘template<class int_type> bool absl::lts_20240722::SimpleAtoi<int_type>’
   63 | ABSL_MUST_USE_RESULT bool SimpleAtoi(absl::string_view str,
      |                           ^~~~~~~~~~
/usr/include/absl/strings/numbers.h:288:51: 错误：‘string_view’不是‘absl’的成员
  288 | ABSL_MUST_USE_RESULT inline bool SimpleAtoi(absl::string_view str,
      |                                                   ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:289:74: 错误：expected primary-expression before ‘out’
  289 |                                             absl::Nonnull<absl::int128*> out) {
      |                                                                          ^~~
/usr/include/absl/strings/numbers.h:293:51: 错误：‘bool absl::lts_20240722::SimpleAtoi’ redeclared as different kind of entity
  293 | ABSL_MUST_USE_RESULT inline bool SimpleAtoi(absl::string_view str,
      |                                                   ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:63:27: 附注：previous declaration ‘template<class int_type> bool absl::lts_20240722::SimpleAtoi<int_type>’
   63 | ABSL_MUST_USE_RESULT bool SimpleAtoi(absl::string_view str,
      |                           ^~~~~~~~~~
/usr/include/absl/strings/numbers.h:293:51: 错误：‘string_view’不是‘absl’的成员
  293 | ABSL_MUST_USE_RESULT inline bool SimpleAtoi(absl::string_view str,
      |                                                   ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:294:75: 错误：expected primary-expression before ‘out’
  294 |                                             absl::Nonnull<absl::uint128*> out) {
      |                                                                           ^~~
/usr/include/absl/strings/numbers.h:299:27: 错误：‘template<class int_type> bool absl::lts_20240722::SimpleHexAtoi’ 重定义
  299 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                           ^~~~~~~~~~~~~
/usr/include/absl/strings/numbers.h:112:27: 附注：‘template<class int_type> bool absl::lts_20240722::SimpleHexAtoi<int_type>’已在此定义过
  112 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                           ^~~~~~~~~~~~~
/usr/include/absl/strings/numbers.h:299:47: 错误：‘string_view’不是‘absl’的成员
  299 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                                               ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:300:66: 错误：expected primary-expression before ‘out’
  300 |                                         absl::Nonnull<int_type*> out) {
      |                                                                  ^~~
/usr/include/absl/strings/numbers.h:305:11: 错误：‘bool absl::lts_20240722::SimpleHexAtoi’ redeclared as different kind of entity
  305 |     absl::string_view str, absl::Nonnull<absl::int128*> out) {
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:112:27: 附注：previous declaration ‘template<class int_type> bool absl::lts_20240722::SimpleHexAtoi<int_type>’
  112 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                           ^~~~~~~~~~~~~
/usr/include/absl/strings/numbers.h:305:11: 错误：‘string_view’不是‘absl’的成员
  305 |     absl::string_view str, absl::Nonnull<absl::int128*> out) {
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:305:57: 错误：expected primary-expression before ‘out’
  305 |     absl::string_view str, absl::Nonnull<absl::int128*> out) {
      |                                                         ^~~
/usr/include/absl/strings/numbers.h:310:11: 错误：‘bool absl::lts_20240722::SimpleHexAtoi’ redeclared as different kind of entity
  310 |     absl::string_view str, absl::Nonnull<absl::uint128*> out) {
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:112:27: 附注：previous declaration ‘template<class int_type> bool absl::lts_20240722::SimpleHexAtoi<int_type>’
  112 | ABSL_MUST_USE_RESULT bool SimpleHexAtoi(absl::string_view str,
      |                           ^~~~~~~~~~~~~
/usr/include/absl/strings/numbers.h:310:11: 错误：‘string_view’不是‘absl’的成员
  310 |     absl::string_view str, absl::Nonnull<absl::uint128*> out) {
      |           ^~~~~~~~~~~
/usr/include/absl/strings/numbers.h:310:58: 错误：expected primary-expression before ‘out’
  310 |     absl::string_view str, absl::Nonnull<absl::uint128*> out) {
      |                                                          ^~~
/usr/include/absl/strings/str_cat.h: In function ‘void absl::lts_20240722::AbslStringify(S&, Hex)’:
/usr/include/absl/strings/str_cat.h:224:25: 错误：‘string_view’不是‘absl’的成员
  224 |       sink.Append(absl::string_view(end - real_width, real_width));
      |                         ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h:231:25: 错误：‘string_view’不是‘absl’的成员
  231 |       sink.Append(absl::string_view(end - hex.width, hex.width));
      |                         ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h: In function ‘void absl::lts_20240722::AbslStringify(S&, Dec)’:
/usr/include/absl/strings/str_cat.h:298:23: 错误：‘string_view’不是‘absl’的成员
  298 |     sink.Append(absl::string_view(writer, static_cast<size_t>(end - writer)));
      |                       ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h: 在全局域：
/usr/include/absl/strings/str_cat.h:360:29: 错误：expected ‘)’ before ‘pc’
  360 |   AlphaNum(absl::string_view pc  // NOLINT(runtime/explicit)
      |           ~                 ^~~
      |                             )
/usr/include/absl/strings/str_cat.h:383:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  383 |   absl::string_view::size_type size() const { return piece_.size(); }
      |         ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h:385:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  385 |   absl::string_view Piece() const { return piece_; }
      |         ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h:418:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  418 |   absl::string_view piece_;
      |         ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(int)’:
/usr/include/absl/strings/str_cat.h:322:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  322 |       : piece_(digits_, static_cast<size_t>(
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(unsigned int)’:
/usr/include/absl/strings/str_cat.h:326:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  326 |       : piece_(digits_, static_cast<size_t>(
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(long int)’:
/usr/include/absl/strings/str_cat.h:330:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  330 |       : piece_(digits_, static_cast<size_t>(
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(long unsigned int)’:
/usr/include/absl/strings/str_cat.h:334:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  334 |       : piece_(digits_, static_cast<size_t>(
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(long long int)’:
/usr/include/absl/strings/str_cat.h:338:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  338 |       : piece_(digits_, static_cast<size_t>(
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(long long unsigned int)’:
/usr/include/absl/strings/str_cat.h:342:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  342 |       : piece_(digits_, static_cast<size_t>(
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(float)’:
/usr/include/absl/strings/str_cat.h:347:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  347 |       : piece_(digits_, numbers_internal::SixDigitsToBuffer(f, digits_)) {}
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(double)’:
/usr/include/absl/strings/str_cat.h:349:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  349 |       : piece_(digits_, numbers_internal::SixDigitsToBuffer(f, digits_)) {}
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(const absl::lts_20240722::strings_internal::AlphaNumBuffer<size>&)’:
/usr/include/absl/strings/str_cat.h:355:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  355 |       : piece_(&buf.data[0], buf.size) {}
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(absl::lts_20240722::Nullable<const char*>)’:
/usr/include/absl/strings/str_cat.h:359:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  359 |       : piece_(NullSafeStringView(c_str)) {}
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h:359:16: 错误：‘NullSafeStringView’在此作用域中尚未声明
  359 |       : piece_(NullSafeStringView(c_str)) {}
      |                ^~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(const T&, absl::lts_20240722::strings_internal::StringifySink&&)’:
/usr/include/absl/strings/str_cat.h:369:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  369 |       : piece_(strings_internal::ExtractStringification(sink, v)) {}
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h:369:34: 错误：‘ExtractStringification’不是‘absl::lts_20240722::strings_internal’的成员
  369 |       : piece_(strings_internal::ExtractStringification(sink, v)) {}
      |                                  ^~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/str_cat.h: In constructor ‘absl::lts_20240722::AlphaNum::AlphaNum(const std::__cxx11::basic_string<char, std::char_traits<char>, _Alloc>&)’:
/usr/include/absl/strings/str_cat.h:375:9: 错误：类‘absl::lts_20240722::AlphaNum’没有名为‘piece_’的字段
  375 |       : piece_(str) {}
      |         ^~~~~~
/usr/include/absl/strings/str_cat.h: In member function ‘const char* absl::lts_20240722::AlphaNum::data() const’:
/usr/include/absl/strings/str_cat.h:384:53: 错误：‘piece_’在此作用域中尚未声明
  384 |   absl::Nullable<const char*> data() const { return piece_.data(); }
      |                                                     ^~~~~~
/usr/include/absl/strings/str_cat.h: 在全局域：
/usr/include/absl/strings/str_cat.h:453:51: 错误：‘string_view’不是‘absl’的成员
  453 | std::string CatPieces(std::initializer_list<absl::string_view> pieces);
      |                                                   ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h:453:51: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/strings/str_cat.h:453:62: 错误：模板第 1 个参数无效
  453 | std::string CatPieces(std::initializer_list<absl::string_view> pieces);
      |                                                              ^
/usr/include/absl/strings/str_cat.h:455:47: 错误：‘string_view’不是‘absl’的成员
  455 |                   std::initializer_list<absl::string_view> pieces);
      |                                               ^~~~~~~~~~~
/usr/include/absl/strings/str_cat.h:455:47: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/strings/str_cat.h:455:58: 错误：模板第 1 个参数无效
  455 |                   std::initializer_list<absl::string_view> pieces);
      |                                                          ^
/usr/include/absl/strings/str_cat.h: In function ‘std::string absl::lts_20240722::StrCat(const AlphaNum&)’:
/usr/include/absl/strings/str_cat.h:538:34: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘size’
  538 |   return std::string(a.data(), a.size());
      |                                  ^~~~
/usr/include/absl/strings/str_cat.h: In function ‘std::string absl::lts_20240722::StrCat(const AlphaNum&, const AlphaNum&, const AlphaNum&, const AlphaNum&, const AlphaNum&, const AV& ...)’:
/usr/include/absl/strings/str_cat.h:553:10: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  553 |       {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |          ^~~~~
/usr/include/absl/strings/str_cat.h:553:21: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  553 |       {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                     ^~~~~
/usr/include/absl/strings/str_cat.h:553:32: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  553 |       {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                                ^~~~~
/usr/include/absl/strings/str_cat.h:553:43: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  553 |       {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                                           ^~~~~
/usr/include/absl/strings/str_cat.h:553:54: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  553 |       {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                                                      ^~~~~
/usr/include/absl/strings/str_cat.h:554:43: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  554 |        static_cast<const AlphaNum&>(args).Piece()...});
      |                                           ^~~~~
/usr/include/absl/strings/str_cat.h:552:37: 错误：cannot convert ‘<花括号内的初始值列表>’ to ‘int’
  552 |   return strings_internal::CatPieces(
      |          ~~~~~~~~~~~~~~~~~~~~~~~~~~~^
      |                                     |
      |                                     <花括号内的初始值列表>
  553 |       {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |       ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  554 |        static_cast<const AlphaNum&>(args).Piece()...});
      |        ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/str_cat.h:453:64: 附注：  初始化‘std::string absl::lts_20240722::strings_internal::CatPieces(int)’的实参 1
  453 | std::string CatPieces(std::initializer_list<absl::string_view> pieces);
      |                       ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~
/usr/include/absl/strings/str_cat.h: In function ‘void absl::lts_20240722::StrAppend(Nonnull<std::__cxx11::basic_string<char>*>, const AlphaNum&, const AlphaNum&, const AlphaNum&, const AlphaNum&, const AlphaNum&, const AV& ...)’:
/usr/include/absl/strings/str_cat.h:599:16: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  599 |       dest, {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                ^~~~~
/usr/include/absl/strings/str_cat.h:599:27: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  599 |       dest, {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                           ^~~~~
/usr/include/absl/strings/str_cat.h:599:38: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  599 |       dest, {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                                      ^~~~~
/usr/include/absl/strings/str_cat.h:599:49: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  599 |       dest, {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                                                 ^~~~~
/usr/include/absl/strings/str_cat.h:599:60: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  599 |       dest, {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |                                                            ^~~~~
/usr/include/absl/strings/str_cat.h:600:49: 错误：‘const class absl::lts_20240722::AlphaNum’ has no member named ‘Piece’
  600 |              static_cast<const AlphaNum&>(args).Piece()...});
      |                                                 ^~~~~
/usr/include/absl/strings/str_cat.h:598:33: 错误：cannot convert ‘<花括号内的初始值列表>’ to ‘int’
  598 |   strings_internal::AppendPieces(
      |   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
      |                                 |
      |                                 <花括号内的初始值列表>
  599 |       dest, {a.Piece(), b.Piece(), c.Piece(), d.Piece(), e.Piece(),
      |       ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  600 |              static_cast<const AlphaNum&>(args).Piece()...});
      |              ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/str_cat.h:455:60: 附注：  初始化‘void absl::lts_20240722::strings_internal::AppendPieces(absl::lts_20240722::Nonnull<std::__cxx11::basic_string<char>*>, int)’的实参 2
  455 |                   std::initializer_list<absl::string_view> pieces);
      |                   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~
/usr/include/absl/container/internal/btree.h: 在全局域：
/usr/include/absl/container/internal/btree.h:112:42: 错误：‘string_view’不是‘absl’的成员
  112 |   StringBtreeDefaultLess(std::less<absl::string_view>) {}  // NOLINT
      |                                          ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:112:42: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:112:53: 错误：模板第 1 个参数无效
  112 |   StringBtreeDefaultLess(std::less<absl::string_view>) {}  // NOLINT
      |                                                     ^
/usr/include/absl/container/internal/btree.h:116:37: 错误：‘string_view’不是‘absl’的成员
  116 |   explicit operator std::less<absl::string_view>() const { return {}; }
      |                                     ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:116:37: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:116:48: 错误：模板第 1 个参数无效
  116 |   explicit operator std::less<absl::string_view>() const { return {}; }
      |                                                ^
/usr/include/absl/container/internal/btree.h:119:40: 错误：‘absl::string_view’尚未声明
  119 |   absl::weak_ordering operator()(absl::string_view lhs,
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:120:40: 错误：‘absl::string_view’尚未声明
  120 |                                  absl::string_view rhs) const {
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:129:40: 错误：‘absl::string_view’尚未声明
  129 |                                  absl::string_view rhs) const {
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:132:40: 错误：‘absl::string_view’尚未声明
  132 |   absl::weak_ordering operator()(absl::string_view lhs,
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h: In member function ‘absl::lts_20240722::weak_ordering absl::lts_20240722::container_internal::StringBtreeDefaultLess::operator()(int, int) const’:
/usr/include/absl/container/internal/btree.h:121:61: 错误：对成员‘compare’的请求出现在‘lhs’中，而后者具有非类类型‘int’
  121 |     return compare_internal::compare_result_as_ordering(lhs.compare(rhs));
      |                                                             ^~~~~~~
/usr/include/absl/container/internal/btree.h: 在全局域：
/usr/include/absl/container/internal/btree.h:144:48: 错误：‘string_view’不是‘absl’的成员
  144 |   StringBtreeDefaultGreater(std::greater<absl::string_view>) {}  // NOLINT
      |                                                ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:144:48: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:144:59: 错误：模板第 1 个参数无效
  144 |   StringBtreeDefaultGreater(std::greater<absl::string_view>) {}  // NOLINT
      |                                                           ^
/usr/include/absl/container/internal/btree.h:148:40: 错误：‘string_view’不是‘absl’的成员
  148 |   explicit operator std::greater<absl::string_view>() const { return {}; }
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:148:40: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:148:51: 错误：模板第 1 个参数无效
  148 |   explicit operator std::greater<absl::string_view>() const { return {}; }
      |                                                   ^
/usr/include/absl/container/internal/btree.h:151:40: 错误：‘absl::string_view’尚未声明
  151 |   absl::weak_ordering operator()(absl::string_view lhs,
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:152:40: 错误：‘absl::string_view’尚未声明
  152 |                                  absl::string_view rhs) const {
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:161:40: 错误：‘absl::string_view’尚未声明
  161 |                                  absl::string_view rhs) const {
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:164:40: 错误：‘absl::string_view’尚未声明
  164 |   absl::weak_ordering operator()(absl::string_view lhs,
      |                                        ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h: In member function ‘absl::lts_20240722::weak_ordering absl::lts_20240722::container_internal::StringBtreeDefaultGreater::operator()(int, int) const’:
/usr/include/absl/container/internal/btree.h:153:61: 错误：对成员‘compare’的请求出现在‘rhs’中，而后者具有非类类型‘int’
  153 |     return compare_internal::compare_result_as_ordering(rhs.compare(lhs));
      |                                                             ^~~~~~~
/usr/include/absl/container/internal/btree.h: 在全局域：
/usr/include/absl/container/internal/btree.h:288:44: 错误：‘string_view’不是‘absl’的成员
  288 | struct key_compare_adapter<std::less<absl::string_view>, absl::string_view> {
      |                                            ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:288:44: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:288:55: 错误：模板第 1 个参数无效
  288 | struct key_compare_adapter<std::less<absl::string_view>, absl::string_view> {
      |                                                       ^
/usr/include/absl/container/internal/btree.h:288:64: 错误：‘string_view’不是‘absl’的成员
  288 | struct key_compare_adapter<std::less<absl::string_view>, absl::string_view> {
      |                                                                ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:288:64: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:288:75: 错误：模板第 1 个参数无效
  288 | struct key_compare_adapter<std::less<absl::string_view>, absl::string_view> {
      |                                                                           ^
/usr/include/absl/container/internal/btree.h:288:75: 错误：模板第 2 个参数无效
/usr/include/absl/container/internal/btree.h:293:47: 错误：‘string_view’不是‘absl’的成员
  293 | struct key_compare_adapter<std::greater<absl::string_view>, absl::string_view> {
      |                                               ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:293:47: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:293:58: 错误：模板第 1 个参数无效
  293 | struct key_compare_adapter<std::greater<absl::string_view>, absl::string_view> {
      |                                                          ^
/usr/include/absl/container/internal/btree.h:293:67: 错误：‘string_view’不是‘absl’的成员
  293 | struct key_compare_adapter<std::greater<absl::string_view>, absl::string_view> {
      |                                                                   ^~~~~~~~~~~
/usr/include/absl/container/internal/btree.h:293:67: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/btree.h:293:78: 错误：模板第 1 个参数无效
  293 | struct key_compare_adapter<std::greater<absl::string_view>, absl::string_view> {
      |                                                                              ^
/usr/include/absl/container/internal/btree.h:293:78: 错误：模板第 2 个参数无效
In file included from /usr/include/absl/hash/internal/hash.h:69,
                 from /usr/include/absl/hash/hash.h:85,
                 from /usr/include/absl/container/internal/hash_function_defaults.h:56,
                 from /usr/include/absl/container/hash_container_defaults.h:19,
                 from /usr/include/absl/container/flat_hash_map.h:43,
                 from /usr/include/google/protobuf/descriptor.h:46:
/usr/include/absl/types/variant.h:54:12: 错误：‘bad_variant_access’ has not been declared in ‘std’
   54 | using std::bad_variant_access;
      |            ^~~~~~~~~~~~~~~~~~
/usr/include/absl/types/variant.h:56:12: 错误：‘get_if’ has not been declared in ‘std’
   56 | using std::get_if;
      |            ^~~~~~
/usr/include/absl/types/variant.h:57:12: 错误：‘holds_alternative’ has not been declared in ‘std’
   57 | using std::holds_alternative;
      |            ^~~~~~~~~~~~~~~~~
/usr/include/absl/types/variant.h:58:12: 错误：‘monostate’ has not been declared in ‘std’
   58 | using std::monostate;
      |            ^~~~~~~~~
/usr/include/absl/types/variant.h:59:12: 错误：‘variant’ has not been declared in ‘std’
   59 | using std::variant;
      |            ^~~~~~~
/usr/include/absl/types/variant.h:60:12: 错误：‘variant_alternative’ has not been declared in ‘std’
   60 | using std::variant_alternative;
      |            ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/types/variant.h:61:12: 错误：‘variant_alternative_t’ has not been declared in ‘std’
   61 | using std::variant_alternative_t;
      |            ^~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/types/variant.h:62:12: 错误：‘variant_npos’ has not been declared in ‘std’
   62 | using std::variant_npos;
      |            ^~~~~~~~~~~~
/usr/include/absl/types/variant.h:63:12: 错误：‘variant_size’ has not been declared in ‘std’
   63 | using std::variant_size;
      |            ^~~~~~~~~~~~
/usr/include/absl/types/variant.h:64:12: 错误：‘variant_size_v’ has not been declared in ‘std’
   64 | using std::variant_size_v;
      |            ^~~~~~~~~~~~~~
/usr/include/absl/types/variant.h:65:12: 错误：‘visit’ has not been declared in ‘std’
   65 | using std::visit;
      |            ^~~~~
/usr/include/absl/types/variant.h: In function ‘To absl::lts_20240722::ConvertVariantTo(Variant&&)’:
/usr/include/absl/types/variant.h:854:16: 错误：‘visit’不是‘absl’的成员
  854 |   return absl::visit(variant_internal::ConversionVisitor<To>{},
      |                ^~~~~
/usr/include/absl/hash/internal/hash.h: 在全局域：
/usr/include/absl/hash/internal/hash.h:565:37: 错误：‘absl::string_view’尚未声明
  565 | H AbslHashValue(H hash_state, absl::string_view str) {
      |                                     ^~~~~~~~~~~
/usr/include/absl/hash/internal/hash.h: In function ‘H absl::lts_20240722::hash_internal::AbslHashValue(H, int)’:
/usr/include/absl/hash/internal/hash.h:567:56: 错误：对成员‘data’的请求出现在‘str’中，而后者具有非类类型‘int’
  567 |       H::combine_contiguous(std::move(hash_state), str.data(), str.size()),
      |                                                        ^~~~
/usr/include/absl/hash/internal/hash.h:567:68: 错误：对成员‘size’的请求出现在‘str’中，而后者具有非类类型‘int’
  567 |       H::combine_contiguous(std::move(hash_state), str.data(), str.size()),
      |                                                                    ^~~~
/usr/include/absl/hash/internal/hash.h:568:11: 错误：对成员‘size’的请求出现在‘str’中，而后者具有非类类型‘int’
  568 |       str.size());
      |           ^~~~
/usr/include/absl/hash/internal/hash.h: 在全局域：
/usr/include/absl/hash/internal/hash.h:834:31: 错误：‘optional’ in namespace ‘absl’ does not name a template type
  834 |     H hash_state, const absl::optional<T>& opt) {
      |                               ^~~~~~~~
/usr/include/absl/hash/internal/hash.h:834:39: 错误：expected ‘,’ or ‘...’ before ‘<’ token
  834 |     H hash_state, const absl::optional<T>& opt) {
      |                                       ^
/usr/include/absl/hash/internal/hash.h: In function ‘typename std::enable_if<absl::lts_20240722::hash_internal::is_hashable<T1>::value, H>::type absl::lts_20240722::hash_internal::AbslHashValue(H, int)’:
/usr/include/absl/hash/internal/hash.h:835:7: 错误：‘opt’在此作用域中尚未声明
  835 |   if (opt) hash_state = H::combine(std::move(hash_state), *opt);
      |       ^~~
/usr/include/absl/hash/internal/hash.h:836:44: 错误：‘opt’在此作用域中尚未声明
  836 |   return H::combine(std::move(hash_state), opt.has_value());
      |                                            ^~~
/usr/include/absl/hash/internal/hash.h: 在全局域：
/usr/include/absl/hash/internal/hash.h:852:41: 错误：‘variant’ in namespace ‘absl’ does not name a template type
  852 | AbslHashValue(H hash_state, const absl::variant<T...>& v) {
      |                                         ^~~~~~~
/usr/include/absl/hash/internal/hash.h:852:48: 错误：expected ‘,’ or ‘...’ before ‘<’ token
  852 | AbslHashValue(H hash_state, const absl::variant<T...>& v) {
      |                                                ^
/usr/include/absl/hash/internal/hash.h: In function ‘typename std::enable_if<absl::lts_20240722::conjunction<absl::lts_20240722::hash_internal::is_hashable<Ts>...>::value, H>::type absl::lts_20240722::hash_internal::AbslHashValue(H, int)’:
/usr/include/absl/hash/internal/hash.h:853:8: 错误：‘v’在此作用域中尚未声明
  853 |   if (!v.valueless_by_exception()) {
      |        ^
/usr/include/absl/hash/internal/hash.h:854:24: 错误：‘visit’不是‘absl’的成员
  854 |     hash_state = absl::visit(VariantVisitor<H>{std::move(hash_state)}, v);
      |                        ^~~~~
/usr/include/absl/hash/internal/hash.h:856:44: 错误：‘v’在此作用域中尚未声明
  856 |   return H::combine(std::move(hash_state), v.index());
      |                                            ^
/usr/include/absl/container/internal/hash_function_defaults.h: 在全局域：
/usr/include/absl/container/internal/hash_function_defaults.h:79:27: 错误：‘absl::string_view’尚未声明
   79 |   size_t operator()(absl::string_view v) const {
      |                           ^~~~~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h: In member function ‘size_t absl::lts_20240722::container_internal::StringHash::operator()(int) const’:
/usr/include/absl/container/internal/hash_function_defaults.h:80:29: 错误：‘string_view’不是‘absl’的成员
   80 |     return absl::Hash<absl::string_view>{}(v);
      |                             ^~~~~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:80:29: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/hash_function_defaults.h:80:40: 错误：模板第 1 个参数无效
   80 |     return absl::Hash<absl::string_view>{}(v);
      |                                        ^
/usr/include/absl/container/internal/hash_function_defaults.h: 在全局域：
/usr/include/absl/container/internal/hash_function_defaults.h:89:25: 错误：‘absl::string_view’尚未声明
   89 |   bool operator()(absl::string_view lhs, absl::string_view rhs) const {
      |                         ^~~~~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:89:48: 错误：‘absl::string_view’尚未声明
   89 |   bool operator()(absl::string_view lhs, absl::string_view rhs) const {
      |                                                ^~~~~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:95:48: 错误：‘absl::string_view’尚未声明
   95 |   bool operator()(const absl::Cord& lhs, absl::string_view rhs) const {
      |                                                ^~~~~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:98:25: 错误：‘absl::string_view’尚未声明
   98 |   bool operator()(absl::string_view lhs, const absl::Cord& rhs) const {
      |                         ^~~~~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h: In member function ‘bool absl::lts_20240722::container_internal::StringEq::operator()(int, const absl::lts_20240722::Cord&) const’:
/usr/include/absl/container/internal/hash_function_defaults.h:99:16: 错误：no match for ‘operator==’ (operand types are ‘int’ and ‘const absl::lts_20240722::Cord’)
   99 |     return lhs == rhs;
      |            ~~~ ^~ ~~~
      |            |      |
      |            int    const absl::lts_20240722::Cord
/usr/include/absl/types/span.h:495:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator==(Span<T>, Span<T>)’
  495 | bool operator==(Span<T> a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:495:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/container/internal/hash_function_defaults.h:99:19: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
   99 |     return lhs == rhs;
      |                   ^~~
/usr/include/absl/types/span.h:499:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator==(Span<const T>, Span<T>)’
  499 | bool operator==(Span<const T> a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:499:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/container/internal/hash_function_defaults.h:99:19: 附注：  mismatched types ‘absl::lts_20240722::Span<const T>’ and ‘int’
   99 |     return lhs == rhs;
      |                   ^~~
/usr/include/absl/types/span.h:503:6: 附注：备选： ‘template<class T> bool absl::lts_20240722::operator==(Span<T>, Span<const T>)’
  503 | bool operator==(Span<T> a, Span<const T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:503:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/container/internal/hash_function_defaults.h:99:19: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
   99 |     return lhs == rhs;
      |                   ^~~
/usr/include/absl/types/span.h:509:6: 附注：备选： ‘template<class T, class U, class> bool absl::lts_20240722::operator==(const U&, Span<T>)’
  509 | bool operator==(const U& a, Span<T> b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:509:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/container/internal/hash_function_defaults.h:99:19: 附注：  ‘absl::lts_20240722::Cord’ is not derived from ‘absl::lts_20240722::Span<T>’
   99 |     return lhs == rhs;
      |                   ^~~
/usr/include/absl/types/span.h:515:6: 附注：备选： ‘template<class T, class U, class> bool absl::lts_20240722::operator==(Span<T>, const U&)’
  515 | bool operator==(Span<T> a, const U& b) {
      |      ^~~~~~~~
/usr/include/absl/types/span.h:515:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/container/internal/hash_function_defaults.h:99:19: 附注：  mismatched types ‘absl::lts_20240722::Span<T>’ and ‘int’
   99 |     return lhs == rhs;
      |                   ^~~
/usr/include/absl/container/inlined_vector.h:943:6: 附注：备选： ‘template<class T, long unsigned int N, class A> bool absl::lts_20240722::operator==(const InlinedVector<T, N, A>&, const InlinedVector<T, N, A>&)’
  943 | bool operator==(const absl::InlinedVector<T, N, A>& a,
      |      ^~~~~~~~
/usr/include/absl/container/inlined_vector.h:943:6: 附注：  template argument deduction/substitution failed:
/usr/include/absl/container/internal/hash_function_defaults.h:99:19: 附注：  mismatched types ‘const absl::lts_20240722::InlinedVector<T, N, A>’ and ‘int’
   99 |     return lhs == rhs;
      |                   ^~~
/usr/include/absl/time/time.h:1774:46: 附注：备选： ‘constexpr bool absl::lts_20240722::operator==(Duration, Duration)’
 1774 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator==(Duration lhs,
      |                                              ^~~~~~~~
/usr/include/absl/time/time.h:1774:66: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::Duration’
 1774 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator==(Duration lhs,
      |                                                         ~~~~~~~~~^~~
/usr/include/absl/time/time.h:892:46: 附注：备选： ‘constexpr bool absl::lts_20240722::operator==(Time, Time)’
  892 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator==(Time lhs, Time rhs) {
      |                                              ^~~~~~~~
/usr/include/absl/time/time.h:892:62: 附注：  no known conversion for argument 1 from ‘int’ to ‘absl::lts_20240722::Time’
  892 | ABSL_ATTRIBUTE_CONST_FUNCTION constexpr bool operator==(Time lhs, Time rhs) {
      |                                                         ~~~~~^~~
/usr/include/absl/numeric/int128.h:798:16: 附注：备选： ‘constexpr bool absl::lts_20240722::operator==(uint128, uint128)’
  798 | constexpr bool operator==(uint128 lhs, uint128 rhs) {
      |                ^~~~~~~~
/usr/include/absl/numeric/int128.h:798:48: 附注：  no known conversion for argument 2 from ‘const absl::lts_20240722::Cord’ to ‘absl::lts_20240722::uint128’
  798 | constexpr bool operator==(uint128 lhs, uint128 rhs) {
      |                                        ~~~~~~~~^~~
/usr/include/absl/numeric/int128_have_intrinsic.inc:199:16: 附注：备选： ‘constexpr bool absl::lts_20240722::operator==(int128, int128)’
  199 | constexpr bool operator==(int128 lhs, int128 rhs) {
      |                ^~~~~~~~
/usr/include/absl/numeric/int128_have_intrinsic.inc:199:46: 附注：  no known conversion for argument 2 from ‘const absl::lts_20240722::Cord’ to ‘absl::lts_20240722::int128’
  199 | constexpr bool operator==(int128 lhs, int128 rhs) {
      |                                       ~~~~~~~^~~
/usr/include/absl/strings/cord.h:1708:13: 附注：备选： ‘bool absl::lts_20240722::operator==(const Cord&, const Cord&)’
 1708 | inline bool operator==(const Cord& lhs, const Cord& rhs) {
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1708:36: 附注：  no known conversion for argument 1 from ‘int’ to ‘const absl::lts_20240722::Cord&’
 1708 | inline bool operator==(const Cord& lhs, const Cord& rhs) {
      |                        ~~~~~~~~~~~~^~~
/usr/include/absl/strings/cord.h:1729:13: 附注：备选： ‘bool absl::lts_20240722::operator==(const Cord&, int)’
 1729 | inline bool operator==(const Cord& lhs, absl::string_view rhs) {
      |             ^~~~~~~~
/usr/include/absl/strings/cord.h:1729:36: 附注：  no known conversion for argument 1 from ‘int’ to ‘const absl::lts_20240722::Cord&’
 1729 | inline bool operator==(const Cord& lhs, absl::string_view rhs) {
      |                        ~~~~~~~~~~~~^~~
/usr/include/absl/container/internal/hash_function_defaults.h: 在全局域：
/usr/include/absl/container/internal/hash_function_defaults.h:112:21: 错误：‘string_view’不是‘absl’的成员
  112 | struct HashEq<absl::string_view> : StringHashEq {};
      |                     ^~~~~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:112:21: 错误：‘string_view’不是‘absl’的成员
/usr/include/absl/container/internal/hash_function_defaults.h:112:32: 错误：模板第 1 个参数无效
  112 | struct HashEq<absl::string_view> : StringHashEq {};
      |                                ^
/usr/include/google/protobuf/descriptor.h:219:22: 错误：‘absl::string_view’尚未声明
  219 |   void SetLazy(absl::string_view name, const FileDescriptor* file);
      |                      ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:285:23: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  285 | PROTOBUF_EXPORT absl::string_view ShortEditionName(Edition edition);
      |                       ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: In function ‘void google::protobuf::AbslStringify(Sink&, Edition)’:
/usr/include/google/protobuf/descriptor.h:294:39: 错误：‘ShortEditionName’不是‘google::protobuf::internal’的成员
  294 |   absl::Format(&sink, "%v", internal::ShortEditionName(edition));
      |                                       ^~~~~~~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: 在全局域：
/usr/include/google/protobuf/descriptor.h:409:48: 错误：‘absl::string_view’尚未声明
  409 |   const FieldDescriptor* FindFieldByName(absl::string_view name) const;
      |                                                ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:415:13: 错误：‘absl::string_view’尚未声明
  415 |       absl::string_view lowercase_name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:422:13: 错误：‘absl::string_view’尚未声明
  422 |       absl::string_view camelcase_name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:439:48: 错误：‘absl::string_view’尚未声明
  439 |   const OneofDescriptor* FindOneofByName(absl::string_view name) const;
      |                                                ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:451:48: 错误：‘absl::string_view’尚未声明
  451 |   const Descriptor* FindNestedTypeByName(absl::string_view name) const;
      |                                                ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:463:50: 错误：‘absl::string_view’尚未声明
  463 |   const EnumDescriptor* FindEnumTypeByName(absl::string_view name) const;
      |                                                  ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:467:56: 错误：‘absl::string_view’尚未声明
  467 |   const EnumValueDescriptor* FindEnumValueByName(absl::string_view name) const;
      |                                                        ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:581:52: 错误：‘absl::string_view’尚未声明
  581 |   const FieldDescriptor* FindExtensionByName(absl::string_view name) const;
      |                                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:586:13: 错误：‘absl::string_view’尚未声明
  586 |       absl::string_view name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:591:13: 错误：‘absl::string_view’尚未声明
  591 |       absl::string_view name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:621:29: 错误：‘absl::string_view’尚未声明
  621 |   bool IsReservedName(absl::string_view name) const;
      |                             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1308:52: 错误：‘absl::string_view’尚未声明
 1308 |   const EnumValueDescriptor* FindValueByName(absl::string_view name) const;
      |                                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1391:29: 错误：‘absl::string_view’尚未声明
 1391 |   bool IsReservedName(absl::string_view name) const;
      |                             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1624:50: 错误：‘absl::string_view’尚未声明
 1624 |   const MethodDescriptor* FindMethodByName(absl::string_view name) const;
      |                                                  ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1880:49: 错误：‘absl::string_view’尚未声明
 1880 |   const Descriptor* FindMessageTypeByName(absl::string_view name) const;
      |                                                 ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1882:50: 错误：‘absl::string_view’尚未声明
 1882 |   const EnumDescriptor* FindEnumTypeByName(absl::string_view name) const;
      |                                                  ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1885:56: 错误：‘absl::string_view’尚未声明
 1885 |   const EnumValueDescriptor* FindEnumValueByName(absl::string_view name) const;
      |                                                        ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1887:52: 错误：‘absl::string_view’尚未声明
 1887 |   const ServiceDescriptor* FindServiceByName(absl::string_view name) const;
      |                                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1890:52: 错误：‘absl::string_view’尚未声明
 1890 |   const FieldDescriptor* FindExtensionByName(absl::string_view name) const;
      |                                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1894:13: 错误：‘absl::string_view’尚未声明
 1894 |       absl::string_view name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:1898:13: 错误：‘absl::string_view’尚未声明
 1898 |       absl::string_view name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2093:46: 错误：‘absl::string_view’尚未声明
 2093 |   const FileDescriptor* FindFileByName(absl::string_view name) const;
      |                                              ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2100:13: 错误：‘absl::string_view’尚未声明
 2100 |       absl::string_view symbol_name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2107:49: 错误：‘absl::string_view’尚未声明
 2107 |   const Descriptor* FindMessageTypeByName(absl::string_view name) const;
      |                                                 ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2108:48: 错误：‘absl::string_view’尚未声明
 2108 |   const FieldDescriptor* FindFieldByName(absl::string_view name) const;
      |                                                ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2109:52: 错误：‘absl::string_view’尚未声明
 2109 |   const FieldDescriptor* FindExtensionByName(absl::string_view name) const;
      |                                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2110:48: 错误：‘absl::string_view’尚未声明
 2110 |   const OneofDescriptor* FindOneofByName(absl::string_view name) const;
      |                                                ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2111:50: 错误：‘absl::string_view’尚未声明
 2111 |   const EnumDescriptor* FindEnumTypeByName(absl::string_view name) const;
      |                                                  ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2112:56: 错误：‘absl::string_view’尚未声明
 2112 |   const EnumValueDescriptor* FindEnumValueByName(absl::string_view name) const;
      |                                                        ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2113:52: 错误：‘absl::string_view’尚未声明
 2113 |   const ServiceDescriptor* FindServiceByName(absl::string_view name) const;
      |                                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2114:50: 错误：‘absl::string_view’尚未声明
 2114 |   const MethodDescriptor* FindMethodByName(absl::string_view name) const;
      |                                                  ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2127:41: 错误：‘absl::string_view’尚未声明
 2127 |       const Descriptor* extendee, absl::string_view printable_name) const;
      |                                         ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2168:18: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 2168 |     static absl::string_view ErrorLocationName(ErrorLocation location);
      |                  ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2178:36: 错误：‘absl::string_view’尚未声明
 2178 |     virtual void RecordError(absl::string_view filename,
      |                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2179:36: 错误：‘absl::string_view’尚未声明
 2179 |                              absl::string_view element_name,
      |                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2181:36: 错误：‘absl::string_view’尚未声明
 2181 |                              absl::string_view message)
      |                                    ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2192:38: 错误：‘absl::string_view’尚未声明
 2192 |     virtual void RecordWarning(absl::string_view filename,
      |                                      ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2193:38: 错误：‘absl::string_view’尚未声明
 2193 |                                absl::string_view element_name,
      |                                      ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2196:38: 错误：‘absl::string_view’尚未声明
 2196 |                                absl::string_view message) {
      |                                      ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2349:35: 错误：‘absl::string_view’尚未声明
 2349 |   bool InternalIsFileLoaded(absl::string_view filename) const;
      |                                   ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2353:39: 错误：‘absl::string_view’尚未声明
 2353 |   void AddUnusedImportTrackFile(absl::string_view file_name,
      |                                       ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2373:37: 错误：‘absl::string_view’尚未声明
 2373 |   bool IsSubSymbolOfBuiltType(absl::string_view name) const;
      |                                     ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2384:13: 错误：‘absl::string_view’尚未声明
 2384 |       absl::string_view name, DeferredValidation& deferred_validation) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2386:13: 错误：‘absl::string_view’尚未声明
 2386 |       absl::string_view name, DeferredValidation& deferred_validation) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2409:40: 错误：‘absl::string_view’尚未声明
 2409 |   Symbol CrossLinkOnDemandHelper(absl::string_view name,
      |                                        ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2413:44: 错误：‘absl::string_view’尚未声明
 2413 |   FileDescriptor* NewPlaceholderFile(absl::string_view name) const;
      |                                            ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2415:13: 错误：‘absl::string_view’尚未声明
 2415 |       absl::string_view name, internal::FlatAllocator& alloc) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2423:31: 错误：‘absl::string_view’尚未声明
 2423 |   Symbol NewPlaceholder(absl::string_view name,
      |                               ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2425:44: 错误：‘absl::string_view’尚未声明
 2425 |   Symbol NewPlaceholderWithMutexHeld(absl::string_view name,
      |                                            ^~~~~~~~~~~
In file included from /usr/include/absl/container/internal/raw_hash_map.h:26,
                 from /usr/include/absl/container/flat_hash_map.h:45:
/usr/include/absl/container/internal/raw_hash_set.h: In instantiation of ‘class absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >’:
/usr/include/absl/container/internal/raw_hash_map.h:33:7:   required from ‘class absl::lts_20240722::container_internal::raw_hash_map<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >’
   33 | class raw_hash_map : public raw_hash_set<Policy, Hash, Eq, Alloc> {
      |       ^~~~~~~~~~~~
/usr/include/absl/container/flat_hash_map.h:128:37:   required from ‘class absl::lts_20240722::flat_hash_map<std::__cxx11::basic_string<char>, bool>’
  128 | class ABSL_INTERNAL_ATTRIBUTE_OWNER flat_hash_map
      |                                     ^~~~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2459:42:   required from here
 2459 |   absl::flat_hash_map<std::string, bool> unused_import_track_files_;
      |                                          ^~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/container/internal/raw_hash_set.h:2388:74: 错误：对‘(const absl::lts_20240722::container_internal::StringHash) (const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type&)’的调用没有匹配
 2388 |   auto KeyTypeCanBeHashed(const Hash& h, const key_type& k) -> decltype(h(k));
      |                                                                         ~^~~
/usr/include/absl/container/internal/hash_function_defaults.h:79:10: 附注：备选： ‘size_t absl::lts_20240722::container_internal::StringHash::operator()(int) const’
   79 |   size_t operator()(absl::string_view v) const {
      |          ^~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:79:39: 附注：  no known conversion for argument 1 from ‘const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type’ {aka ‘const std::__cxx11::basic_string<char>’} to ‘int’
   79 |   size_t operator()(absl::string_view v) const {
      |                     ~~~~~~~~~~~~~~~~~~^
/usr/include/absl/container/internal/hash_function_defaults.h:82:10: 附注：备选： ‘size_t absl::lts_20240722::container_internal::StringHash::operator()(const absl::lts_20240722::Cord&) const’
   82 |   size_t operator()(const absl::Cord& v) const {
      |          ^~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:82:39: 附注：  no known conversion for argument 1 from ‘const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type’ {aka ‘const std::__cxx11::basic_string<char>’} to ‘const absl::lts_20240722::Cord&’
   82 |   size_t operator()(const absl::Cord& v) const {
      |                     ~~~~~~~~~~~~~~~~~~^
/usr/include/absl/container/internal/raw_hash_set.h:2389:70: 错误：对‘(const absl::lts_20240722::container_internal::StringEq) (const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type&, const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type&)’的调用没有匹配
 2389 |   auto KeyTypeCanBeEq(const Eq& eq, const key_type& k) -> decltype(eq(k, k));
      |                                                                    ~~^~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:89:8: 附注：备选： ‘bool absl::lts_20240722::container_internal::StringEq::operator()(int, int) const’
   89 |   bool operator()(absl::string_view lhs, absl::string_view rhs) const {
      |        ^~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:89:37: 附注：  no known conversion for argument 1 from ‘const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type’ {aka ‘const std::__cxx11::basic_string<char>’} to ‘int’
   89 |   bool operator()(absl::string_view lhs, absl::string_view rhs) const {
      |                   ~~~~~~~~~~~~~~~~~~^~~
/usr/include/absl/container/internal/hash_function_defaults.h:92:8: 附注：备选： ‘bool absl::lts_20240722::container_internal::StringEq::operator()(const absl::lts_20240722::Cord&, const absl::lts_20240722::Cord&) const’
   92 |   bool operator()(const absl::Cord& lhs, const absl::Cord& rhs) const {
      |        ^~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:92:37: 附注：  no known conversion for argument 1 from ‘const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type’ {aka ‘const std::__cxx11::basic_string<char>’} to ‘const absl::lts_20240722::Cord&’
   92 |   bool operator()(const absl::Cord& lhs, const absl::Cord& rhs) const {
      |                   ~~~~~~~~~~~~~~~~~~^~~
/usr/include/absl/container/internal/hash_function_defaults.h:95:8: 附注：备选： ‘bool absl::lts_20240722::container_internal::StringEq::operator()(const absl::lts_20240722::Cord&, int) const’
   95 |   bool operator()(const absl::Cord& lhs, absl::string_view rhs) const {
      |        ^~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:95:37: 附注：  no known conversion for argument 1 from ‘const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type’ {aka ‘const std::__cxx11::basic_string<char>’} to ‘const absl::lts_20240722::Cord&’
   95 |   bool operator()(const absl::Cord& lhs, absl::string_view rhs) const {
      |                   ~~~~~~~~~~~~~~~~~~^~~
/usr/include/absl/container/internal/hash_function_defaults.h:98:8: 附注：备选： ‘bool absl::lts_20240722::container_internal::StringEq::operator()(int, const absl::lts_20240722::Cord&) const’
   98 |   bool operator()(absl::string_view lhs, const absl::Cord& rhs) const {
      |        ^~~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:98:37: 附注：  no known conversion for argument 1 from ‘const absl::lts_20240722::container_internal::raw_hash_set<absl::lts_20240722::container_internal::FlatHashMapPolicy<std::__cxx11::basic_string<char>, bool>, absl::lts_20240722::container_internal::StringHash, absl::lts_20240722::container_internal::StringEq, std::allocator<std::pair<const std::__cxx11::basic_string<char>, bool> > >::key_type’ {aka ‘const std::__cxx11::basic_string<char>’} to ‘int’
   98 |   bool operator()(absl::string_view lhs, const absl::Cord& rhs) const {
      |                   ~~~~~~~~~~~~~~~~~~^~~
/usr/include/google/protobuf/descriptor.h:2467:13: 错误：‘absl::string_view’尚未声明
 2467 |       absl::string_view message_name) const;
      |             ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: In member function ‘const google::protobuf::OneofDescriptor* google::protobuf::Descriptor::real_oneof_decl(int) const’:
/usr/include/google/protobuf/descriptor.h:2513:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 2513 |   ABSL_DCHECK(index < real_oneof_decl_count());
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: 在全局域：
/usr/include/google/protobuf/descriptor.h:2623:13: 错误：‘bool google::protobuf::Descriptor::IsReservedName’ is not a static data member of ‘class google::protobuf::Descriptor’
 2623 | inline bool Descriptor::IsReservedName(absl::string_view name) const {
      |             ^~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2623:46: 错误：‘string_view’不是‘absl’的成员
 2623 | inline bool Descriptor::IsReservedName(absl::string_view name) const {
      |                                              ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2642:13: 错误：‘bool google::protobuf::EnumDescriptor::IsReservedName’ is not a static data member of ‘class google::protobuf::EnumDescriptor’
 2642 | inline bool EnumDescriptor::IsReservedName(absl::string_view name) const {
      |             ^~~~~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2642:50: 错误：‘string_view’不是‘absl’的成员
 2642 | inline bool EnumDescriptor::IsReservedName(absl::string_view name) const {
      |                                                  ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: In member function ‘int google::protobuf::FieldDescriptor::index_in_oneof() const’:
/usr/include/google/protobuf/descriptor.h:2679:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 2679 |   ABSL_DCHECK(is_oneof_);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: In member function ‘const google::protobuf::Descriptor* google::protobuf::FieldDescriptor::extension_scope() const’:
/usr/include/google/protobuf/descriptor.h:2684:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 2684 |   ABSL_CHECK(is_extension_);
      |   ^~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: In member function ‘const google::protobuf::OneofDescriptor* google::protobuf::FieldDescriptor::real_containing_oneof() const’:
/usr/include/google/protobuf/descriptor.h:2717:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 2717 |     ABSL_DCHECK(!res->is_synthetic());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h: 在全局域：
/usr/include/google/protobuf/descriptor.h:2881:30: 错误：‘string_view’不是‘absl’的成员
 2881 | bool ParseNoReflection(absl::string_view from, google::protobuf::MessageLite& to);
      |                              ^~~~~~~~~~~
/usr/include/google/protobuf/descriptor.h:2881:77: 错误：expected primary-expression before ‘&’ token
 2881 | bool ParseNoReflection(absl::string_view from, google::protobuf::MessageLite& to);
      |                                                                             ^
/usr/include/google/protobuf/descriptor.h:2881:79: 错误：‘to’ was not declared in this scope; did you mean ‘io’?
 2881 | bool ParseNoReflection(absl::string_view from, google::protobuf::MessageLite& to);
      |                                                                               ^~
      |                                                                               io
/usr/include/google/protobuf/descriptor.h:2881:81: 错误：expression list treated as compound expression in initializer [-fpermissive]
 2881 | bool ParseNoReflection(absl::string_view from, google::protobuf::MessageLite& to);
      |                                                                                 ^
/usr/include/google/protobuf/descriptor.h:2932:52: 错误：‘string_view’不是‘absl’的成员
 2932 | PROTOBUF_EXPORT bool IsLazilyInitializedFile(absl::string_view filename);
      |                                                    ^~~~~~~~~~~
In file included from /usr/include/google/protobuf/generated_message_reflection.h:26:
/usr/include/google/protobuf/generated_enum_reflection.h:53:43: 错误：‘absl::string_view’尚未声明
   53 |                                     absl::string_view name, int* value);
      |                                           ^~~~~~~~~~~
/usr/include/google/protobuf/generated_enum_reflection.h:56:61: 错误：‘absl::string_view’尚未声明
   56 | bool ParseNamedEnum(const EnumDescriptor* descriptor, absl::string_view name,
      |                                                             ^~~~~~~~~~~
In file included from /usr/include/google/protobuf/generated_message_reflection.h:28:
/usr/include/google/protobuf/unknown_field_set.h:198:54: 错误：‘absl::string_view’尚未声明
  198 | inline void WriteLengthDelimited(uint32_t num, absl::string_view val,
      |                                                      ^~~~~~~~~~~
/usr/include/google/protobuf/unknown_field_set.h: In function ‘void google::protobuf::internal::WriteLengthDelimited(uint32_t, int, google::protobuf::UnknownFieldSet*)’:
/usr/include/google/protobuf/unknown_field_set.h:200:48: 错误：对成员‘data’的请求出现在‘val’中，而后者具有非类类型‘int’
  200 |   unknown->AddLengthDelimited(num)->assign(val.data(), val.size());
      |                                                ^~~~
/usr/include/google/protobuf/unknown_field_set.h:200:60: 错误：对成员‘size’的请求出现在‘val’中，而后者具有非类类型‘int’
  200 |   unknown->AddLengthDelimited(num)->assign(val.data(), val.size());
      |                                                            ^~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::GetFieldOffsetNonOneof(const google::protobuf::FieldDescriptor*) const’:
/usr/include/google/protobuf/generated_message_reflection.h:124:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  124 |     ABSL_DCHECK(!InRealOneof(field));
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::HasBitIndex(const google::protobuf::FieldDescriptor*) const’:
/usr/include/google/protobuf/generated_message_reflection.h:156:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  156 |     ABSL_DCHECK(HasHasbits());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::HasBitsOffset() const’:
/usr/include/google/protobuf/generated_message_reflection.h:162:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  162 |     ABSL_DCHECK(HasHasbits());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::InlinedStringIndex(const google::protobuf::FieldDescriptor*) const’:
/usr/include/google/protobuf/generated_message_reflection.h:171:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  171 |     ABSL_DCHECK(HasInlinedString());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::InlinedStringDonatedOffset() const’:
/usr/include/google/protobuf/generated_message_reflection.h:177:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  177 |     ABSL_DCHECK(HasInlinedString());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::GetExtensionSetOffset() const’:
/usr/include/google/protobuf/generated_message_reflection.h:194:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  194 |     ABSL_DCHECK(HasExtensionSet());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::SplitOffset() const’:
/usr/include/google/protobuf/generated_message_reflection.h:229:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  229 |     ABSL_DCHECK(IsSplit());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_reflection.h: In member function ‘uint32_t google::protobuf::internal::ReflectionSchema::SizeofSplit() const’:
/usr/include/google/protobuf/generated_message_reflection.h:234:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  234 |     ABSL_DCHECK(IsSplit());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /usr/include/google/protobuf/message.h:110,
                 from /home/kbrd/libopenshot/build/src/objdetectdata.pb.h:27:
/usr/include/google/protobuf/map.h: 在全局域：
/usr/include/google/protobuf/map.h:236:58: 错误：‘string_view’不是‘absl’的成员
  236 |                             std::is_convertible<T, absl::string_view>::value>>
      |                                                          ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:236:58: 错误：‘string_view’不是‘absl’的成员
/usr/include/google/protobuf/map.h:236:69: 错误：模板第 2 个参数无效
  236 |                             std::is_convertible<T, absl::string_view>::value>>
      |                                                                     ^
/usr/include/google/protobuf/map.h:236:72: 错误：模板第 1 个参数无效
  236 |                             std::is_convertible<T, absl::string_view>::value>>
      |                                                                        ^~~~~
/usr/include/google/protobuf/map.h:237:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  237 |   static absl::string_view ImplicitConvertImpl(T&& str, Rank2) {
      |                ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:243:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  243 |   static absl::string_view ImplicitConvertImpl(T&& str, Rank1) {
      |                ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:248:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  248 |   static absl::string_view ImplicitConvertImpl(T&& str, Rank0) {
      |                ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:253:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  253 |   static absl::string_view ImplicitConvert(T&& str) {
      |                ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:257:41: 错误：‘string_view’不是‘absl’的成员
  257 |   struct hash : public absl::Hash<absl::string_view> {
      |                                         ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:257:41: 错误：‘string_view’不是‘absl’的成员
/usr/include/google/protobuf/map.h:257:52: 错误：模板第 1 个参数无效
  257 |   struct hash : public absl::Hash<absl::string_view> {
      |                                                    ^
/usr/include/google/protobuf/map.h:276:26: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  276 |   using ViewType = absl::string_view;
      |                          ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:278:10: 错误：‘ViewType’ does not name a type; did you mean ‘FieldType’?
  278 |   static ViewType ToView(const T& v) {
      |          ^~~~~~~~
      |          FieldType
/usr/include/google/protobuf/map.h: In member function ‘size_t google::protobuf::internal::TransparentSupport<std::__cxx11::basic_string<char> >::hash::operator()(T&&) const’:
/usr/include/google/protobuf/map.h:262:31: 错误：‘string_view’不是‘absl’的成员
  262 |       return absl::Hash<absl::string_view>::operator()(
      |                               ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:262:31: 错误：‘string_view’不是‘absl’的成员
/usr/include/google/protobuf/map.h:262:42: 错误：模板第 1 个参数无效
  262 |       return absl::Hash<absl::string_view>::operator()(
      |                                          ^
/usr/include/google/protobuf/map.h: 在全局域：
/usr/include/google/protobuf/map.h:342:40: 错误：expected ‘)’ before ‘v’
  342 |   explicit VariantKey(absl::string_view v)
      |                      ~                 ^~
      |                                        )
/usr/include/google/protobuf/map.h: In member function ‘size_t google::protobuf::internal::VariantKey::Hash() const’:
/usr/include/google/protobuf/map.h:351:47: 错误：‘string_view’不是‘absl’的成员
  351 |                            : absl::Hash<absl::string_view>{}(
      |                                               ^~~~~~~~~~~
/usr/include/google/protobuf/map.h:351:47: 错误：‘string_view’不是‘absl’的成员
/usr/include/google/protobuf/map.h:351:58: 错误：模板第 1 个参数无效
  351 |                            : absl::Hash<absl::string_view>{}(
      |                                                          ^
/usr/include/google/protobuf/map.h:352:40: 错误：‘string_view’不是‘absl’的成员
  352 |                                  absl::string_view(data, integral));
      |                                        ^~~~~~~~~~~
/usr/include/google/protobuf/map.h: In member function ‘google::protobuf::internal::VariantKey google::protobuf::internal::RealKeyToVariantKey<std::__cxx11::basic_string<char> >::operator()(const T&) const’:
/usr/include/google/protobuf/map.h:381:56: 错误：‘ImplicitConvert’不是‘google::protobuf::internal::TransparentSupport<std::__cxx11::basic_string<char> >’的成员
  381 |     return VariantKey(TransparentSupport<std::string>::ImplicitConvert(value));
      |                                                        ^~~~~~~~~~~~~~~
/usr/include/google/protobuf/map.h: In function ‘google::protobuf::internal::NodeBase* google::protobuf::internal::TableEntryToNode(TableEntryPtr)’:
/usr/include/google/protobuf/map.h:412:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  412 |   ABSL_DCHECK(TableEntryIsList(entry));
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/map.h: In function ‘google::protobuf::internal::TableEntryPtr google::protobuf::internal::NodeToTableEntry(NodeBase*)’:
/usr/include/google/protobuf/map.h:416:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  416 |   ABSL_DCHECK((reinterpret_cast<uintptr_t>(node) & 1) == 0);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/map.h: In function ‘google::protobuf::internal::TreeForMap* google::protobuf::internal::TableEntryToTree(TableEntryPtr)’:
/usr/include/google/protobuf/map.h:420:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  420 |   ABSL_DCHECK(TableEntryIsTree(entry));
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/map.h: In function ‘google::protobuf::internal::TableEntryPtr google::protobuf::internal::TreeToTableEntry(TreeForMap*)’:
/usr/include/google/protobuf/map.h:424:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  424 |   ABSL_DCHECK((reinterpret_cast<uintptr_t>(node) & 1) == 0);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/map.h: In member function ‘void google::protobuf::internal::UntypedMapIterator::SearchFrom(google::protobuf::internal::map_index_t)’:
/usr/include/google/protobuf/map.h:812:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  812 |   ABSL_DCHECK(m_->index_of_first_non_null_ == m_->num_buckets_ ||
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/map.h:822:7: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  822 |       ABSL_DCHECK(!tree->empty());
      |       ^~~~~~~~~~~
      |       |
      |       const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/message.h: 在全局域：
/usr/include/google/protobuf/message.h:392:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  392 |   static absl::string_view GetTypeNameImpl(const ClassData* data);
      |                ^~~~~~~~~~~
/usr/include/google/protobuf/message.h:628:11: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  628 |     absl::string_view CopyFromCord(const absl::Cord& cord) {
      |           ^~~~~~~~~~~
/usr/include/google/protobuf/message.h:645:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  645 |   absl::string_view GetStringView(
      |         ^~~~~~~~~~~
/usr/include/google/protobuf/message.h:771:9: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  771 |   absl::string_view GetRepeatedStringView(
      |         ^~~~~~~~~~~
/usr/include/google/protobuf/message.h:954:57: 错误：‘absl::string_view’尚未声明
  954 |   const FieldDescriptor* FindKnownExtensionByName(absl::string_view name) const;
      |                                                         ^~~~~~~~~~~
/usr/include/google/protobuf/message.h: In function ‘const T* google::protobuf::DownCastMessage(const MessageLite*) [with T = Message]’:
/usr/include/google/protobuf/message.h:1477:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 1477 |   ABSL_DCHECK(DynamicCastMessage<Message>(from) == from)
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/message.h: In member function ‘const void* google::protobuf::Reflection::GetSplitField(const google::protobuf::Message*) const’:
/usr/include/google/protobuf/message.h:1550:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 1550 |   ABSL_DCHECK(schema_.IsSplit());
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/message.h: In member function ‘void** google::protobuf::Reflection::MutableSplitField(google::protobuf::Message*) const’:
/usr/include/google/protobuf/message.h:1556:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 1556 |   ABSL_DCHECK(schema_.IsSplit());
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /home/kbrd/libopenshot/build/src/objdetectdata.pb.h:31:
/usr/include/google/protobuf/timestamp.pb.h: 在全局域：
/usr/include/google/protobuf/timestamp.pb.h:191:18: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  191 |   static ::absl::string_view FullMessageName() { return "google.protobuf.Timestamp"; }
      |                  ^~~~~~~~~~~
/usr/include/google/protobuf/timestamp.pb.h: In member function ‘void google::protobuf::Timestamp::UnsafeArenaSwap(google::protobuf::Timestamp*)’:
/usr/include/google/protobuf/timestamp.pb.h:139:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  139 |     ABSL_DCHECK(GetArena() == other->GetArena());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h: 在全局域：
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h:199:18: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  199 |   static ::absl::string_view FullMessageName() { return "pb_objdetect.Frame.Box"; }
      |                  ^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h: In member function ‘void pb_objdetect::Frame_Box::UnsafeArenaSwap(pb_objdetect::Frame_Box*)’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h:147:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  147 |     ABSL_DCHECK(GetArena() == other->GetArena());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h: 在全局域：
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h:459:18: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  459 |   static ::absl::string_view FullMessageName() { return "pb_objdetect.Frame"; }
      |                  ^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h: In member function ‘void pb_objdetect::Frame::UnsafeArenaSwap(pb_objdetect::Frame*)’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h:407:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  407 |     ABSL_DCHECK(GetArena() == other->GetArena());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h: 在全局域：
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h:667:18: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
  667 |   static ::absl::string_view FullMessageName() { return "pb_objdetect.ObjDetect"; }
      |                  ^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h: In member function ‘void pb_objdetect::ObjDetect::UnsafeArenaSwap(pb_objdetect::ObjDetect*)’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.h:615:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  615 |     ABSL_DCHECK(GetArena() == other->GetArena());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
In file included from /home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:11:
/usr/include/google/protobuf/generated_message_tctable_impl.h: 在全局域：
/usr/include/google/protobuf/generated_message_tctable_impl.h:888:42: 错误：‘absl::string_view’尚未声明
  888 |                                    absl::string_view value);
      |                                          ^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_impl.h:902:51: 错误：‘absl::string_view’尚未声明
  902 |                                             absl::string_view value) {
      |                                                   ^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_impl.h:1030:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1030 |   static absl::string_view MessageName(const TcParseTableBase* table);
      |                ^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_impl.h:1031:16: 错误：‘string_view’不是命名空间‘absl’中的一个类型名
 1031 |   static absl::string_view FieldName(const TcParseTableBase* table,
      |                ^~~~~~~~~~~
/usr/include/google/protobuf/generated_message_tctable_impl.h:1041:34: 错误：‘absl::string_view’尚未声明
 1041 |   static bool MpVerifyUtf8(absl::string_view wire_bytes,
      |                                  ^~~~~~~~~~~
/usr/include/google/protobuf/wire_format.h: In static member function ‘static void google::protobuf::internal::WireFormat::SerializeWithCachedSizes(const google::protobuf::Message&, int, google::protobuf::io::CodedOutputStream*)’:
/usr/include/google/protobuf/wire_format.h:109:5: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char [43], int, std::string&)’
  109 |     ABSL_CHECK_EQ(output->ByteCount(), expected_endpoint)
      |     ^~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:355:3: 附注：备选： ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’
  355 |   LogMessageFatal(const char* file, int line,
      |   ^~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  no known conversion for argument 3 from ‘std::string’ {aka ‘std::__cxx11::basic_string<char>’} to ‘int’
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:354:3: 附注：备选： ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int)’
  354 |   LogMessageFatal(const char* file, int line) ABSL_ATTRIBUTE_COLD;
      |   ^~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:354:3: 附注： 备选需要 2 实参，但提供了 3 个
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc: In member function ‘void pb_objdetect::Frame_Box::SharedDtor()’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:246:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  246 |   ABSL_DCHECK(GetArena() == nullptr);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc: In member function ‘void pb_objdetect::Frame::SharedDtor()’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:594:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  594 |   ABSL_DCHECK(GetArena() == nullptr);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc: In member function ‘void pb_objdetect::ObjDetect::SharedDtor()’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:858:3: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  858 |   ABSL_DCHECK(GetArena() == nullptr);
      |   ^~~~~~~~~~~
      |   |
      |   const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc: In member function ‘virtual void pb_objdetect::ObjDetect::Clear()’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:953:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  953 |     ABSL_DCHECK(_impl_.last_updated_ != nullptr);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc: In static member function ‘static void pb_objdetect::ObjDetect::MergeImpl(google::protobuf::MessageLite&, const google::protobuf::MessageLite&)’:
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:1071:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
 1071 |     ABSL_DCHECK(from._impl_.last_updated_ != nullptr);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/bind.h: In instantiation of ‘absl::lts_20240722::str_format_internal::FormatSpecTemplate<Args>::FormatSpecTemplate(const char*) [with absl::lts_20240722::FormatConversionCharSet ...Args = {(absl::lts_20240722::FormatConversionCharSet)655355}]’:
/usr/include/absl/crc/crc32c.h:184:34:   required from here
  184 |   return os << absl::StreamFormat("%08x", static_cast<uint32_t>(crc));
      |                ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/strings/internal/str_format/bind.h:167:45: 错误：no matching function for call to ‘absl::lts_20240722::UntypedFormatSpec::UntypedFormatSpec(const char*&)’
  167 |   FormatSpecTemplate(const char* s) : Base(s) {}  // NOLINT
      |                                             ^
/usr/include/absl/strings/str_format.h:114:12: 附注：备选： ‘absl::lts_20240722::UntypedFormatSpec::UntypedFormatSpec(absl::lts_20240722::Nonnull<const absl::lts_20240722::str_format_internal::ParsedFormatBase*>)’
  114 |   explicit UntypedFormatSpec(
      |            ^~~~~~~~~~~~~~~~~
/usr/include/absl/strings/str_format.h:115:67: 附注：  no known conversion for argument 1 from ‘const char*’ to ‘absl::lts_20240722::Nonnull<const absl::lts_20240722::str_format_internal::ParsedFormatBase*>’ {aka ‘const absl::lts_20240722::str_format_internal::ParsedFormatBase*’}
  115 |       absl::Nonnull<const str_format_internal::ParsedFormatBase*> pc)
      |       ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/usr/include/absl/log/internal/log_message.h: In instantiation of ‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(const char (&)[SIZE]) [with int SIZE = 19]’:
/usr/include/google/protobuf/arena_align.h:159:47:   required from here
  159 |   ABSL_DCHECK(absl::has_single_bit(align)) << "Invalid alignment " << align;
      |                                               ^~~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:305:44: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer<absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral>(const char [19])’
  305 |   CopyToEncodedBuffer<StringType::kLiteral>(buf);
      |   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：备选： ‘void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(int) [with StringType str_type = absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral]’ (near match)
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：  conversion of argument 1 would be ill-formed:
/usr/include/absl/log/internal/log_message.h:235:8: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
      |        |
      |        const char*
/usr/include/absl/log/internal/log_message.h:237:8: 附注：备选： ‘template<absl::lts_20240722::log_internal::LogMessage::StringType str_type> void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(char, size_t)’
  237 |   void CopyToEncodedBuffer(char ch, size_t num) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:237:8: 附注： 备选需要 2 实参，但提供了 1 个
/usr/include/absl/log/internal/log_message.h: In instantiation of ‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(const char (&)[SIZE]) [with int SIZE = 17]’:
/usr/include/google/protobuf/message_lite.h:1032:10:   required from here
 1032 |       << "Cannot downcast " << from.GetTypeName() << " to " << to.GetTypeName();
      |          ^~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:305:44: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer<absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral>(const char [17])’
  305 |   CopyToEncodedBuffer<StringType::kLiteral>(buf);
      |   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：备选： ‘void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(int) [with StringType str_type = absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral]’ (near match)
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：  conversion of argument 1 would be ill-formed:
/usr/include/absl/log/internal/log_message.h:235:8: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
      |        |
      |        const char*
/usr/include/absl/log/internal/log_message.h:237:8: 附注：备选： ‘template<absl::lts_20240722::log_internal::LogMessage::StringType str_type> void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(char, size_t)’
  237 |   void CopyToEncodedBuffer(char ch, size_t num) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:237:8: 附注： 备选需要 2 实参，但提供了 1 个
/usr/include/absl/log/internal/log_message.h: In instantiation of ‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(const char (&)[SIZE]) [with int SIZE = 5]’:
/usr/include/google/protobuf/message_lite.h:1032:54:   required from here
 1032 |       << "Cannot downcast " << from.GetTypeName() << " to " << to.GetTypeName();
      |                                                      ^~~~~~
/usr/include/absl/log/internal/log_message.h:305:44: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer<absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral>(const char [5])’
  305 |   CopyToEncodedBuffer<StringType::kLiteral>(buf);
      |   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：备选： ‘void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(int) [with StringType str_type = absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral]’ (near match)
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：  conversion of argument 1 would be ill-formed:
/usr/include/absl/log/internal/log_message.h:235:8: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
      |        |
      |        const char*
/usr/include/absl/log/internal/log_message.h:237:8: 附注：备选： ‘template<absl::lts_20240722::log_internal::LogMessage::StringType str_type> void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(char, size_t)’
  237 |   void CopyToEncodedBuffer(char ch, size_t num) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:237:8: 附注： 备选需要 2 实参，但提供了 1 个
/usr/include/google/protobuf/parse_context.h: In instantiation of ‘const char* google::protobuf::internal::EpsCopyInputStream::AppendUntilEnd(const char*, const A&) [with A = google::protobuf::internal::EpsCopyInputStream::AppendString(const char*, std::string*)::<lambda(const char*, ptrdiff_t)>]’:
/usr/include/google/protobuf/parse_context.h:428:26:   required from here
  428 |     return AppendUntilEnd(
      |            ~~~~~~~~~~~~~~^
  429 |         ptr, [str](const char* p, ptrdiff_t s) { str->append(p, s); });
      |         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/parse_context.h:421:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  421 |     ABSL_DCHECK(end >= ptr);
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/extension_set.h: In instantiation of ‘bool google::protobuf::internal::ExtensionSet::FindExtensionInfoFromFieldNumber(int, int, ExtensionFinder*, google::protobuf::internal::ExtensionInfo*, bool*) const [with ExtensionFinder = google::protobuf::internal::GeneratedExtensionFinder]’:
/usr/include/google/protobuf/extension_set.h:884:44:   required from here
  884 |     return FindExtensionInfoFromFieldNumber(wire_type, field, &finder,
      |            ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~
  885 |                                             extension, was_packed_on_wire);
      |                                             ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/extension_set.h:844:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  844 |     ABSL_DCHECK(extension->type > 0 &&
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h: In instantiation of ‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(const char (&)[SIZE]) [with int SIZE = 12]’:
/usr/include/google/protobuf/message.h:1478:55:   required from here
 1478 |       << "Cannot downcast " << from->GetTypeName() << " to Message";
      |                                                       ^~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:305:44: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer<absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral>(const char [12])’
  305 |   CopyToEncodedBuffer<StringType::kLiteral>(buf);
      |   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：备选： ‘void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(int) [with StringType str_type = absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral]’ (near match)
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：  conversion of argument 1 would be ill-formed:
/usr/include/absl/log/internal/log_message.h:235:8: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
      |        |
      |        const char*
/usr/include/absl/log/internal/log_message.h:237:8: 附注：备选： ‘template<absl::lts_20240722::log_internal::LogMessage::StringType str_type> void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(char, size_t)’
  237 |   void CopyToEncodedBuffer(char ch, size_t num) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:237:8: 附注： 备选需要 2 实参，但提供了 1 个
/usr/include/absl/log/internal/log_message.h: In instantiation of ‘absl::lts_20240722::log_internal::LogMessage& absl::lts_20240722::log_internal::LogMessage::operator<<(const char (&)[SIZE]) [with int SIZE = 27]’:
/usr/include/google/protobuf/generated_message_tctable_impl.h:550:21:   required from ‘static constexpr const char* (* google::protobuf::internal::TcParser::SingularVarintNoZag1())(google::protobuf::MessageLite*, const char*, google::protobuf::internal::ParseContext*, google::protobuf::internal::TcFieldData, const google::protobuf::internal::TcParseTableBase*, uint64_t) [with FieldType = unsigned int; int unused_data_offset = 32; int unused_hasbit_idx = 63; google::protobuf::internal::TailCallParseFunc = const char* (*)(google::protobuf::MessageLite*, const char*, google::protobuf::internal::ParseContext*, google::protobuf::internal::TcFieldData, const google::protobuf::internal::TcParseTableBase*, long unsigned int)]’
  550 |     ABSL_LOG(FATAL) << "This should be unreachable";
      |                     ^
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:311:98:   required from here
  311 | :TcParser::SingularVarintNoZag1<::uint32_t, offsetof(Frame_Box, _impl_.classid_), 63>(),
      | ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~

/usr/include/absl/log/internal/log_message.h:305:44: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer<absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral>(const char [27])’
  305 |   CopyToEncodedBuffer<StringType::kLiteral>(buf);
      |   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：备选： ‘void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(int) [with StringType str_type = absl::lts_20240722::log_internal::LogMessage::StringType::kLiteral]’ (near match)
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:235:8: 附注：  conversion of argument 1 would be ill-formed:
/usr/include/absl/log/internal/log_message.h:235:8: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  235 |   void CopyToEncodedBuffer(absl::string_view str) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
      |        |
      |        const char*
/usr/include/absl/log/internal/log_message.h:237:8: 附注：备选： ‘template<absl::lts_20240722::log_internal::LogMessage::StringType str_type> void absl::lts_20240722::log_internal::LogMessage::CopyToEncodedBuffer(char, size_t)’
  237 |   void CopyToEncodedBuffer(char ch, size_t num) ABSL_ATTRIBUTE_NOINLINE;
      |        ^~~~~~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:237:8: 附注： 备选需要 2 实参，但提供了 1 个
/usr/include/google/protobuf/arena.h: In instantiation of ‘static T* google::protobuf::Arena::CreateArray(google::protobuf::Arena*, size_t) [with T = unsigned char; size_t = long unsigned int]’:
/usr/include/google/protobuf/map.h:128:38:   required from ‘google::protobuf::internal::MapAllocator<U>::value_type* google::protobuf::internal::MapAllocator<U>::allocate(size_type, const void*) [with U = google::protobuf::internal::NodeBase; pointer = google::protobuf::internal::NodeBase*; size_type = long unsigned int]’
  128 |           Arena::CreateArray<uint8_t>(arena_, n * sizeof(value_type)));
      |           ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/map.h:661:47:   required from here
  661 |     return AllocFor<NodeBase>(alloc_).allocate(node_size / sizeof(NodeBase));
      |            ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/arena.h:266:5: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char [37], int, std::string&)’
  266 |     ABSL_CHECK_LE(num_elements, std::numeric_limits<size_t>::max() / sizeof(T))
      |     ^~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:355:3: 附注：备选： ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’
  355 |   LogMessageFatal(const char* file, int line,
      |   ^~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  no known conversion for argument 3 from ‘std::string’ {aka ‘std::__cxx11::basic_string<char>’} to ‘int’
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:354:3: 附注：备选： ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int)’
  354 |   LogMessageFatal(const char* file, int line) ABSL_ATTRIBUTE_COLD;
      |   ^~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:354:3: 附注： 备选需要 2 实参，但提供了 3 个
/usr/include/google/protobuf/repeated_ptr_field.h: In instantiation of ‘void google::protobuf::internal::RepeatedPtrFieldBase::Destroy() [with TypeHandler = google::protobuf::internal::GenericTypeHandler<pb_objdetect::Frame_Box>]’:
/usr/include/google/protobuf/repeated_ptr_field.h:1288:25:   required from ‘google::protobuf::RepeatedPtrField<T>::~RepeatedPtrField() [with Element = pb_objdetect::Frame_Box]’
 1288 |     Destroy<TypeHandler>();
      |     ~~~~~~~~~~~~~~~~~~~~^~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:61:9:   required from here
   61 |       : bounding_box_{},
      |         ^~~~~~~~~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h:213:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  213 |     ABSL_DCHECK(NeedsDestroy());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h: In instantiation of ‘void google::protobuf::internal::RepeatedPtrFieldBase::Destroy() [with TypeHandler = google::protobuf::internal::GenericTypeHandler<pb_objdetect::Frame>]’:
/usr/include/google/protobuf/repeated_ptr_field.h:1288:25:   required from ‘google::protobuf::RepeatedPtrField<T>::~RepeatedPtrField() [with Element = pb_objdetect::Frame]’
 1288 |     Destroy<TypeHandler>();
      |     ~~~~~~~~~~~~~~~~~~~~^~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:88:9:   required from here
   88 |         frame_{},
      |         ^~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h:213:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  213 |     ABSL_DCHECK(NeedsDestroy());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h: In instantiation of ‘void google::protobuf::internal::RepeatedPtrFieldBase::Destroy() [with TypeHandler = google::protobuf::internal::GenericTypeHandler<std::__cxx11::basic_string<char> >]’:
/usr/include/google/protobuf/repeated_ptr_field.h:1288:25:   required from ‘google::protobuf::RepeatedPtrField<T>::~RepeatedPtrField() [with Element = std::__cxx11::basic_string<char>]’
 1288 |     Destroy<TypeHandler>();
      |     ~~~~~~~~~~~~~~~~~~~~^~
/home/kbrd/libopenshot/build/src/objdetectdata.pb.cc:89:9:   required from here
   89 |         classnames_{},
      |         ^~~~~~~~~~~~~
/usr/include/google/protobuf/repeated_ptr_field.h:213:5: 错误：invalid conversion from ‘const char*’ to ‘int’ [-fpermissive]
  213 |     ABSL_DCHECK(NeedsDestroy());
      |     ^~~~~~~~~~~
      |     |
      |     const char*
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  初始化‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’的实参 3
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/google/protobuf/arena.h: In instantiation of ‘static T* google::protobuf::Arena::CreateArray(google::protobuf::Arena*, size_t) [with T = char; size_t = long unsigned int]’:
/usr/include/google/protobuf/repeated_field.h:964:62:   required from ‘void google::protobuf::RepeatedField< <模板形参-1-1> >::GrowNoAnnotate(int, int) [with Element = unsigned int]’
  964 |     new_rep = reinterpret_cast<Rep*>(Arena::CreateArray<char>(arena, bytes));
      |                                      ~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~
/usr/include/google/protobuf/repeated_field.h:998:3:   required from ‘void google::protobuf::RepeatedField< <模板形参-1-1> >::Grow(int, int) [with Element = unsigned int]’
  998 |   GrowNoAnnotate(current_size, new_size);
      |   ^~~~~~~~~~~~~~
/usr/include/google/protobuf/repeated_field.h:657:5:   required from ‘void google::protobuf::RepeatedField< <模板形参-1-1> >::Add(Element) [with Element = unsigned int]’
  657 |     Grow(size(), size() + 1);
      |     ^~~~
/usr/include/google/protobuf/wire_format_lite.h:1095:14:   required from ‘static bool google::protobuf::internal::WireFormatLite::ReadRepeatedFixedSizePrimitive(int, uint32_t, google::protobuf::io::CodedInputStream*, google::protobuf::RepeatedField<Element>*) [with CType = unsigned int; FieldType DeclaredType = google::protobuf::internal::WireFormatLite::TYPE_FIXED32; uint32_t = unsigned int]’
 1095 |   values->Add(value);
      |   ~~~~~~~~~~~^~~~~~~
/usr/include/google/protobuf/wire_format_lite.h:1146:1:   required from here
 1146 | READ_REPEATED_FIXED_SIZE_PRIMITIVE(uint32_t, TYPE_FIXED32)
      | ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/google/protobuf/arena.h:266:5: 错误：no matching function for call to ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char [37], int, std::string&)’
  266 |     ABSL_CHECK_LE(num_elements, std::numeric_limits<size_t>::max() / sizeof(T))
      |     ^~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:355:3: 附注：备选： ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int, int)’
  355 |   LogMessageFatal(const char* file, int line,
      |   ^~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:356:37: 附注：  no known conversion for argument 3 from ‘std::string’ {aka ‘std::__cxx11::basic_string<char>’} to ‘int’
  356 |                   absl::string_view failure_msg) ABSL_ATTRIBUTE_COLD;
      |                   ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:354:3: 附注：备选： ‘absl::lts_20240722::log_internal::LogMessageFatal::LogMessageFatal(const char*, int)’
  354 |   LogMessageFatal(const char* file, int line) ABSL_ATTRIBUTE_COLD;
      |   ^~~~~~~~~~~~~~~
/usr/include/absl/log/internal/log_message.h:354:3: 附注： 备选需要 2 实参，但提供了 3 个
/usr/include/absl/strings/cord.h: In instantiation of ‘H absl::lts_20240722::Cord::HashFragmented(H) const [with H = absl::lts_20240722::hash_internal::MixingHashState]’:
/usr/include/absl/strings/cord.h:824:28:   required from ‘H absl::lts_20240722::AbslHashValue(H, const Cord&) [with H = hash_internal::MixingHashState]’
  824 |     return c.HashFragmented(std::move(hash_state));
      |            ~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/hash/internal/hash.h:948:27:   required from ‘static absl::lts_20240722::enable_if_t<((bool)std::is_same<H, decltype (absl::lts_20240722::hash_internal::AbslHashValue(std::move(state), value))>::value), H> absl::lts_20240722::hash_internal::HashSelect::HashValueProbe::Invoke(H, const T&) [with H = absl::lts_20240722::hash_internal::MixingHashState; T = absl::lts_20240722::Cord; absl::lts_20240722::enable_if_t<((bool)std::is_same<H, decltype (absl::lts_20240722::hash_internal::AbslHashValue(std::move(state), value))>::value), H> = absl::lts_20240722::hash_internal::MixingHashState; decltype (absl::lts_20240722::hash_internal::AbslHashValue(std::move(state), value)) = absl::lts_20240722::hash_internal::MixingHashState]’
  948 |       return AbslHashValue(std::move(state), value);
      |              ~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/hash/internal/hash.h:1321:73:   required from ‘static H absl::lts_20240722::hash_internal::HashStateBase<H>::combine(H, const T&, const Ts& ...) [with T = absl::lts_20240722::Cord; Ts = {}; H = absl::lts_20240722::hash_internal::MixingHashState]’
 1321 |   return H::combine(hash_internal::HashSelect::template Apply<T>::Invoke(
      |                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^
 1322 |                         std::move(state), value),
      |                         ~~~~~~~~~~~~~~~~~~~~~~~~                         
/usr/include/absl/hash/internal/hash.h:1056:39:   required from ‘static size_t absl::lts_20240722::hash_internal::MixingHashState::hash(const T&) [with T = absl::lts_20240722::Cord; typename std::enable_if<(! absl::lts_20240722::conjunction<std::is_integral<_Tp>, absl::lts_20240722::hash_internal::is_uniquely_represented<T, void> >::value), int>::type <匿名> = 0; size_t = long unsigned int]’
 1056 |     return static_cast<size_t>(combine(MixingHashState{}, value).state_);
      |                                ~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/absl/hash/internal/hash.h:1310:33:   required from ‘size_t absl::lts_20240722::hash_internal::HashImpl<T>::operator()(const T&) const [with T = absl::lts_20240722::Cord; size_t = long unsigned int]’
 1310 |     return MixingHashState::hash(value);
      |            ~~~~~~~~~~~~~~~~~~~~~^~~~~~~
/usr/include/absl/container/internal/hash_function_defaults.h:83:36:   required from here
   83 |     return absl::Hash<absl::Cord>{}(v);
      |            ~~~~~~~~~~~~~~~~~~~~~~~~^~~
/usr/include/absl/strings/cord.h:1102:18: 错误：cannot convert ‘absl::lts_20240722::Cord::HashFragmented<absl::lts_20240722::hash_internal::MixingHashState>(absl::lts_20240722::hash_internal::MixingHashState) const::<lambda(int)>’ to ‘int’
 1102 |     ForEachChunk([&combiner, &hash_state](absl::string_view chunk) {
      |                  ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
      |                  |
      |                  absl::lts_20240722::Cord::HashFragmented<absl::lts_20240722::hash_internal::MixingHashState>(absl::lts_20240722::hash_internal::MixingHashState) const::<lambda(int)>
 1103 |       hash_state = combiner.add_buffer(std::move(hash_state), chunk.data(),
      |       ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 1104 |                                        chunk.size());
      |                                        ~~~~~~~~~~~~~~
 1105 |     });
      |     ~             
/usr/include/absl/strings/cord.h:1698:48: 附注：  初始化‘void absl::lts_20240722::Cord::ForEachChunk(int) const’的实参 1
 1698 |     absl::FunctionRef<void(absl::string_view)> callback) const {
      |     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~
make[2]: *** [src/CMakeFiles/openshot.dir/build.make:1168：src/CMakeFiles/openshot.dir/objdetectdata.pb.cc.o] 错误 1
make[1]: *** [CMakeFiles/Makefile2:933：src/CMakeFiles/openshot.dir/all] 错误 2
make: *** [Makefile:166：all] 错误 2
