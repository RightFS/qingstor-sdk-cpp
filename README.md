# QingStor SDK for C and C++


The official QingStor SDK for the C and C++ programming language.

The project is implemented with C++.
It also provides C style interface ( C wrapper for C++ interface ). 
Restful API related code in this project is generated by [snips][snips link] (A code generator for RESTful APIs).

## Getting Started

### Installation

Refer to the [Installation Guide][installation guide], and have this SDK installed.

### Preparation

Before your start, please go to [QingCloud Console][console link] to create a pair of QingCloud API AccessKey.

___API AccessKey Example:___

``` yaml
access_key_id: 'ACCESS_KEY_ID_EXAMPLE'
secret_access_key: 'SECRET_ACCESS_KEY_EXAMPLE'
```
### Usage

Now you are ready to code. You can read the detailed guides in the list below to have a clear understanding.
If you are programing with C++ language, we recommend you to use the modern C++ interface and read `Usage Guide for QingStor C++ style interface`.
And if you are programing with C language, you should chose the C style interface and read `Usage Guide for QingStor  style interface`.

- [Configuration Guide][config guide]
- [Usage Guide for QingStor C style interface][c style usage]
- [Usage Guide for QingStor C++ style interface][cpp style usage]

Checkout our [RELEASE][release link] and [CHANGELOGS][change logs link] for information about the latest features, bug fixes and new ideas.

### Running tests:

Several directories are appended with *tests. After building your project, you can run these executables to ensure everything works properly.
Tests here is mplementated based on [Cucumber test framework][cucumber link].

## Reference Documentations

- [QingStor Documentation][documentation link]
- [QingStor Guide][guide link]
- [QingStor APIs][api doc link]
- [QingStor API Specs][api specs link]
- [QingStor SDK Test Scenarios][sdk test scenarios link]       

## Contributing

1. Fork it ( https://github.com/yunify/qingstor-sdk-c-and-cpp/fork )
2. Create your feature branch (`git checkout -b new-feature`)
3. Commit your changes (`git commit -asm 'Add some feature'`)
4. Push to the branch (`git push origin new-feature`)
5. Create a new Pull Request

## LICENSE

The Apache License (Version 2.0, January 2004).

[snips link]: https://github.com/yunify/snips
[installation guide]: docs/installation.md
[console link]: https://console.qingcloud.com/access_keys/
[c style usage]: docs/sdk_c_style_usage.md
[cpp style usage]: docs/sdk_cpp_style_usage.md
[config guide]: docs/configuration.md
[release link]: https://github.com/yunify/qingstor-sdk-c-and-cpp/releases
[change logs link]: https://github.com/yunify/qingstor-sdk-net/blob/master/CHANGELOGS
[documentation link]: https://docs.qingcloud.com/qingstor/index.html
[guide link]: https://docs.qingcloud.com/qingstor/index.html
[api doc link]: https://docs.qingcloud.com/qingstor/api/index.html
[api specs link]: https://github.com/yunify/qingstor-api-specs
[sdk test scenarios link]: https://github.com/yunify/qingstor-sdk-test-scenarios
[cucumber link]: https://github.com/cucumber/cucumber-cpp