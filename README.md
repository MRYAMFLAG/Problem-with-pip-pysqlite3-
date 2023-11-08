# Problem-with-pip-pysqlite3-
How can I solve this problem? I downloaded the setuptools and wheel commands, and this is how it appears for me?

**                  **
Collecting pysqlite3
  Using cached pysqlite3-0.5.2.tar.gz (40 kB)
  Preparing metadata (setup.py) ... done
Building wheels for collected packages: pysqlite3
  Building wheel for pysqlite3 (setup.py) ... error
  error: subprocess-exited-with-error

  × python setup.py bdist_wheel did not run successfully.
  │ exit code: 1
  ╰─> [12 lines of output]
      running bdist_wheel
      running build
      running build_py
      creating build
      creating build\lib.win-amd64-cpython-39
      creating build\lib.win-amd64-cpython-39\pysqlite3
      copying pysqlite3\dbapi2.py -> build\lib.win-amd64-cpython-39\pysqlite3
      copying pysqlite3\__init__.py -> build\lib.win-amd64-cpython-39\pysqlite3
      running build_ext
      Builds a C extension linking against libsqlite3 library
      building 'pysqlite3._sqlite3' extension
      error: Microsoft Visual C++ 14.0 or greater is required. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for pysqlite3
  Running setup.py clean for pysqlite3
Failed to build pysqlite3
ERROR: Could not build wheels for pysqlite3, which is required to install pyproject.toml-based projects

**                                                                                                     **
