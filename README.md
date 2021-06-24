# Ishiko/C++ Project Documentation

Ishiko/C++ is a set of C++ libraries.

This repository contains the project documentation.

## Contents

### Ishiko/C++ original projects

- [Collections](https://github.com/ishiko-cpp/collections): Container classes.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/collections.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/collections)

- [Config](https://github.com/ishiko-cpp/config): Configuration classes.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/config.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/config)

- [Crypto](https://github.com/ishiko-cpp/Crypto): Cryptographic functions.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/Crypto.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/Crypto)

- [Diff](https://github.com/ishiko-cpp/diff): Diff utilities.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/diff.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/diff)

- [Errors](https://github.com/ishiko-cpp/errors): Code to handle and report errors.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/errors.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/errors)

- [FileSystem](https://github.com/ishiko-cpp/filesystem): Utilities to work with the file system.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/filesystem.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/filesystem)

- [Hash](https://github.com/ishiko-cpp/Hash): A library to calculate hashes.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/Hash.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/Hash)

- [Platform](https://github.com/ishiko-cpp/platform): Code to handle differences between operating systems.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/platform.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/platform)

- [Process](https://github.com/ishiko-cpp/process): Code to work with processes and environment variables.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/process.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/process)

- [Tasks](https://github.com/ishiko-cpp/Tasks): A framework to schedule and execute tasks.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/Tasks.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/Tasks)

- [Terminal](https://github.com/ishiko-cpp/Terminal): Utilities to work with terminal input and output.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/Terminal.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/Terminal)

- [Tests](https://github.com/ishiko-cpp/tests): A C++ test framework.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/tests.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/tests)

- [Text](https://github.com/ishiko-cpp/text): Utilities to work with text data.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/text.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/text)

- [Types](https://github.com/ishiko-cpp/types): Fundamental types.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/types.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/types)

- [UUIDs](https://github.com/ishiko-cpp/UUIDs): UUID types.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/UUIDs.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/UUIDs)

- [XML](https://github.com/ishiko-cpp/xml): XML utilities.

  [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/xml.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/xml)

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
1. FileSystem (without the test code)
1. XML (without the test code)
1. Hash (without the test code)
1. Diff (without the test code)
1. Tests
1. Platform (now with the test code)
1. Errors (now with the test code)
1. Types (now with the test code)
1. Text (now with the test code)
1. Process (now with the test code)
1. FileSystem (now with the test code)
1. XML (now with the test code)
1. Hash (now with the test code)
1. Diff (now with the test code)
1. Collections
1. Crypto
1. Terminal
1. Tasks
1. UUIDs

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
