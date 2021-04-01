# Ishiko/C++ - Project Documentation

Ishiko/C++ is a set of C++ libraries.

This repository contains the project documentation.

## Contents

### Ishiko/C++ original projects

- [Collections](https://github.com/Ishiko-cpp/Collections): Container classes.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Collections.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Collections)

- [Crypto](https://github.com/Ishiko-cpp/Crypto): Cryptographic functions.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Crypto.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Crypto)

- [Errors](https://github.com/Ishiko-cpp/Errors): Code to handle and report errors.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Errors.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Errors)

- [FileSystem](https://github.com/Ishiko-cpp/FileSystem): Utilities to work with the file system.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/FileSystem.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/FileSystem)

- [Platform](https://github.com/Ishiko-cpp/Platform): Code to handle differences between operating systems.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Platform.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Platform)

- [Process](https://github.com/Ishiko-cpp/Process): Code to work with processes and environment variables.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Process.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Process)

- [Tasks](https://github.com/Ishiko-cpp/Tasks): A framework to schedule and execute tasks.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Tasks.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Tasks)

- [Terminal](https://github.com/Ishiko-cpp/Terminal): Utilities to work with terminal input and output.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Terminal.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Terminal)

- [TestFramework](https://github.com/Ishiko-cpp/TestFramework): A C++ test framework.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/TestFramework.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/TestFramework)

- [Text](https://github.com/Ishiko-cpp/Text): Utilities to work with text data.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Text.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Text)

- [Types](https://github.com/Ishiko-cpp/Types): Fundamental types.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/Types.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/Types)

- [UUID](https://github.com/Ishiko-cpp/UUID): UUID types.

  [![Ishiko-cpp](https://circleci.com/gh/Ishiko-cpp/UUID.svg?style=shield)](https://circleci.com/gh/Ishiko-cpp/UUID)

### Third party dependencies/forks

- [Botan](https://github.com/Ishiko-cpp/botan): Botan is a C++ cryptography library.
- [G3log](https://github.com/Ishiko-cpp/g3log): G3log is an asynchronous, "crash safe", logger.
- [pugixml](https://github.com/Ishiko-cpp/pugixml): Light-weight, simple and fast XML parser for C++ with XPath support

# Usage

## Building the projects from scratch

The following build order can be used to build the projects from scratch:

1. Botan
1. pugixml
1. Platform (without the test code)
1. Errors (without the test code)
1. Types (without the test code)
1. Text (without the test code)
1. Process (without the test code)
1. TestFramework
1. Platform (now with the test code)
1. Errors (now with the test code)
1. Types (now with the test code)
1. Text (now with the test code)
1. Process (now with the test code)
1. Collections
1. Crypto
1. FileSystem
1. Terminal
1. Tasks
1. UUID

# Support

None.

## License

Copyright (c) 2005-2021 Xavier Leclercq

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
