# travis_qmake_gcc_cpp11_boost_oclint

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp11_boost_oclint.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp11_boost_oclint)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++11`
 * Libraries: `STL` and `Boost`
 * Code coverage: none
 * Static type checking: `OCLint`
 * Source: one single file, `main.cpp`

More complex builds:
 * Add `Boost.Test`: [travis_qmake_gcc_cpp11_boost_test_oclint](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_boost_test_oclint)

Simpler builds:
 * No OCLint: [travis_qmake_gcc_cpp11_boost](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_boost)
 * No Boost: [travis_qmake_gcc_cpp11_oclint](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_oclint)
