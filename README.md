# Ishiko/C++ Project Documentation

Ishiko/C++ is a set of C++ libraries.

This repository contains the project documentation.

## Contents

### Ishiko/C++ original projects

1. [BasePlatform](https://github.com/ishiko-cpp/base-platform): code to handle differences between operating systems.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/base-platform.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/base-platform)

1. [Collections](https://github.com/ishiko-cpp/collections): container classes.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/collections.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/collections)

1. [Config](https://github.com/ishiko-cpp/config): configuration classes.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/config.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/config)

1. [Crypto](https://github.com/ishiko-cpp/Crypto): cryptographic functions.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/Crypto.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/Crypto)

1. [CSV](https://github.com/ishiko-cpp/csv): CSV utilities.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/csv.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/csv)

1. [Diff](https://github.com/ishiko-cpp/diff): diff utilities.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/diff.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/diff)

1. [Errors](https://github.com/ishiko-cpp/errors): code to handle and report errors.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/errors.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/errors)

1. [FileSystem](https://github.com/ishiko-cpp/filesystem): utilities to work with the file system.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/filesystem.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/filesystem)

1. [Hash](https://github.com/ishiko-cpp/hash): a library to calculate hashes.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/hash.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/hash)

1. [Networking](https://github.com/ishiko-cpp/networking): networking.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/networking.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/networking)

1. [Process](https://github.com/ishiko-cpp/process): code to work with processes and environment variables.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/process.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/process)

1. [Terminal](https://github.com/ishiko-cpp/terminal): utilities to work with terminal input and output.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/terminal.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/terminal)

1. [Tests](https://github.com/ishiko-cpp/tests): a C++ test framework.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/tests.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/tests)

1. [Text](https://github.com/ishiko-cpp/text): utilities to work with text data.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/text.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/text)

1. [Types](https://github.com/ishiko-cpp/types): fundamental types.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/types.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/types)

1. [UserTasks](https://github.com/ishiko-cpp/user-tasks): a framework to schedule and execute tasks.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/user-tasks.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/user-tasks)

1. [UUIDs](https://github.com/ishiko-cpp/uuids): UUID types.

   [![ishiko-cpp](https://circleci.com/gh/ishiko-cpp/uuids.svg?style=shield)](https://circleci.com/gh/ishiko-cpp/uuids)
 
1. [XML](https://github.com/ishiko-cpp/xml): XML utilities.

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
1. BasePlatform (without the test code)
1. Errors (without the test code)
1. Types (without the test code)
1. Collections (without the test code)
1. Text (without the test code)
1. Process (without the test code)
1. FileSystem (without the test code)
1. XML (without the test code)
1. Hash (without the test code)
1. Diff (without the test code)
1. Tests
1. BasePlatform (now with the test code)
1. Errors (now with the test code)
1. Types (now with the test code)
1. Collections (now with the test code)
1. Text (now with the test code)
1. Process (now with the test code)
1. FileSystem (now with the test code)
1. XML (now with the test code)
1. Hash (now with the test code)
1. Diff (now with the test code)
1. Crypto
1. Terminal
1. Tasks
1. UUIDs
1. Networking
1. CSV

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
