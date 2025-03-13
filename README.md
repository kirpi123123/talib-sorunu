# talib-sorunu

C:\Users\aliem\OneDrive\Desktop\bot>cd C:\ta-lib

C:\ta-lib>pip install TA-Lib
Collecting TA-Lib
  Using cached ta_lib-0.6.3.tar.gz (376 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Installing backend dependencies ... done
  Preparing metadata (pyproject.toml) ... done
Requirement already satisfied: setuptools in c:\program files\windowsapps\pythonsoftwarefoundation.python.3.11_3.11.2544.0_x64__qbz5n2kfra8p0\lib\site-packages (from TA-Lib) (65.5.0)
Requirement already satisfied: numpy in c:\users\aliem\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from TA-Lib) (2.2.3)
Building wheels for collected packages: TA-Lib
  Building wheel for TA-Lib (pyproject.toml) ... error
  error: subprocess-exited-with-error

  × Building wheel for TA-Lib (pyproject.toml) did not run successfully.
  │ exit code: 1
  ╰─> [364 lines of output]
      <string>:83: UserWarning: Cannot find ta-lib library, installation may fail.
      C:\Users\aliem\AppData\Local\Temp\pip-build-env-h3lrdzfr\overlay\Lib\site-packages\setuptools\config\_apply_pyprojecttoml.py:81: SetuptoolsWarning: `install_requires` overwritten in `pyproject.toml` (dependencies)
        corresp(dist, value, root_dir)
      running bdist_wheel
      running build
      running build_py
      creating build\lib.win-amd64-cpython-311\talib
      copying talib\abstract.py -> build\lib.win-amd64-cpython-311\talib
      copying talib\deprecated.py -> build\lib.win-amd64-cpython-311\talib
      copying talib\stream.py -> build\lib.win-amd64-cpython-311\talib
      copying talib\__init__.py -> build\lib.win-amd64-cpython-311\talib
      running egg_info
      writing ta_lib.egg-info\PKG-INFO
      writing dependency_links to ta_lib.egg-info\dependency_links.txt
      writing requirements to ta_lib.egg-info\requires.txt
      writing top-level names to ta_lib.egg-info\top_level.txt
      reading manifest file 'ta_lib.egg-info\SOURCES.txt'
      reading manifest template 'MANIFEST.in'
      adding license file 'LICENSE'
      adding license file 'AUTHORS'
      writing manifest file 'ta_lib.egg-info\SOURCES.txt'
      copying talib\_abstract.pxi -> build\lib.win-amd64-cpython-311\talib
      copying talib\_common.pxi -> build\lib.win-amd64-cpython-311\talib
      copying talib\_func.pxi -> build\lib.win-amd64-cpython-311\talib
      copying talib\_stream.pxi -> build\lib.win-amd64-cpython-311\talib
      copying talib\_ta_lib.c -> build\lib.win-amd64-cpython-311\talib
      copying talib\_ta_lib.pyi -> build\lib.win-amd64-cpython-311\talib
      copying talib\_ta_lib.pyx -> build\lib.win-amd64-cpython-311\talib
      copying talib\py.typed -> build\lib.win-amd64-cpython-311\talib
      running build_ext
      building 'talib._ta_lib' extension
      creating build\temp.win-amd64-cpython-311\Release\talib
      "C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.43.34808\bin\HostX86\x64\cl.exe" /c /nologo /O2 /W3 /GL /DNDEBUG /MD -Ic:\ta-lib\c\include "-Ic:\Program Files\TA-Lib\include" "-Ic:\Program Files (x86)\TA-Lib\include" -IC:\Users\aliem\AppData\Local\Temp\pip-build-env-h3lrdzfr\normal\Lib\site-packages\numpy\_core\include "-IC:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.11_3.11.2544.0_x64__qbz5n2kfra8p0\include" "-IC:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.11_3.11.2544.0_x64__qbz5n2kfra8p0\Include" "-IC:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.43.34808\include" "-IC:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Auxiliary\VS\include" "-IC:\Program Files (x86)\Windows Kits\10\include\10.0.22621.0\ucrt" "-IC:\Program Files (x86)\Windows Kits\10\\include\10.0.22621.0\\um" "-IC:\Program Files (x86)\Windows Kits\10\\include\10.0.22621.0\\shared" "-IC:\Program Files (x86)\Windows Kits\10\\include\10.0.22621.0\\winrt" "-IC:\Program Files (x86)\Windows Kits\10\\include\10.0.22621.0\\cppwinrt" /Tctalib/_ta_lib.c /Fobuild\temp.win-amd64-cpython-311\Release\talib\_ta_lib.obj
      _ta_lib.c
      C:\Users\aliem\AppData\Local\Temp\pip-build-env-h3lrdzfr\normal\Lib\site-packages\numpy\_core\include\numpy\npy_1_7_deprecated_api.h(14) : Warning Msg: Using deprecated NumPy API, disable it with #define NPY_NO_DEPRECATED_API NPY_1_7_API_VERSION
      talib/_ta_lib.c(12749): warning C4244: '=': 'npy_intp' - 'npy_int' d”n\x81Ÿ\x81m\x81; veri kayb\x8d olabilir
      talib/_ta_lib.c(12794): warning C4244: '=': 'npy_intp' - 'npy_int' d”n\x81Ÿ\x81m\x81; veri kayb\x8d olabilir
      talib/_ta_lib.c(12848): warning C4244: '=': 'npy_intp' - 'npy_int' d”n\x81Ÿ\x81m\x81; veri kayb\x8d olabilir
      talib/_ta_lib.c(12911): warning C4244: '=': 'npy_intp' - 'npy_int' d”n\x81Ÿ\x81m\x81; veri kayb\x8d olabilir
      talib/_ta_lib.c(13148): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(13234): warning C4013: 'TA_ACCBANDS_Lookback' tan\x8dms\x8dz; int d”nd\x81ren extern oldu§u varsay\x8dl\x8dyor
      talib/_ta_lib.c(13251): warning C4013: 'TA_ACCBANDS' tan\x8dms\x8dz; int d”nd\x81ren extern oldu§u varsay\x8dl\x8dyor
      talib/_ta_lib.c(14027): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(14032): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(14273): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(14506): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(14733): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(14738): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(14943): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(15168): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(15725): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(16165): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(16233): warning C4013: 'TA_AVGDEV_Lookback' tan\x8dms\x8dz; int d”nd\x81ren extern oldu§u varsay\x8dl\x8dyor
      talib/_ta_lib.c(16240): warning C4013: 'TA_AVGDEV' tan\x8dms\x8dz; int d”nd\x81ren extern oldu§u varsay\x8dl\x8dyor
      talib/_ta_lib.c(16386): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(16626): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(17088): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(32047): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(32247): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(32774): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(33180): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(33383): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(34941): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(35018): warning C4013: 'TA_IMI_Lookback' tan\x8dms\x8dz; int d”nd\x81ren extern oldu§u varsay\x8dl\x8dyor
      talib/_ta_lib.c(35025): warning C4013: 'TA_IMI' tan\x8dms\x8dz; int d”nd\x81ren extern oldu§u varsay\x8dl\x8dyor
      talib/_ta_lib.c(35136): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(35321): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(35506): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(35691): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(35876): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(36405): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(36619): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(36624): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(36629): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(36899): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(36909): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(36919): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(37134): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(37600): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(37605): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(37805): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(37990): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(38424): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(38635): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(38835): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(39030): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(39215): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(39413): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(39613): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(39866): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(40084): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(40279): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(40685): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(41109): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(41327): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(41546): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(41551): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(41741): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(41926): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(42111): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(42296): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(42481): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(43554): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(43917): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44185): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44190): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44200): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44477): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44482): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44741): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44746): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(44751): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(45147): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(45344): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(45866): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(46265): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(46450): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(46635): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(47088): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(47093): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(47098): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(47313): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(47747): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(47950): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(59000): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(59859): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(59864): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(60104): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(60333): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(60556): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(60561): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(60756): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(60976): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(61506): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(61941): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(62152): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(62384): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(62838): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(77722): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(77912): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(78412): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(78801): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(79000): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(80472): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(80660): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(80835): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(81010): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(81185): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(81360): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(81859): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(82063): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(82068): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(82073): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(82335): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(82345): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(82355): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(82562): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(83012): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(83017): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(83210): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(83385): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(83789): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(83999): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(84189): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(84377): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(84552): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(84727): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(84919): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(85141): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(85355): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(85543): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(85932): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(86345): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(86559): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(86771): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(86776): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(86956): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(87131): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(87306): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(87481): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(87656): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(88685): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89028): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89286): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89291): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89301): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89576): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89581): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89838): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89843): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(89848): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(90229): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(90416): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(90908): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(91293): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(91468): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(91643): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(92082): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(92087): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(92092): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(92303): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(92723): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(92922): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96154): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96184): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96186): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96204): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96219): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96234): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96236): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96259): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96274): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96299): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96319): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96334): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96364): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96384): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96779): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96794): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96819): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96839): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96854): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96909): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96924): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96939): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96954): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96969): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(96984): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97009): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97029): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97031): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97033): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97054): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97058): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97062): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97094): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97129): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97131): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97154): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97169): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97189): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97204): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97219): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97234): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97249): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97264): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97279): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97294): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97309): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97324): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97344): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97364): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97379): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97394): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97396): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97419): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97434): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97449): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97464): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97479): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97574): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97594): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97614): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97616): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97620): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97649): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97651): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97674): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97676): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97678): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97709): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97724): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97754): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97774): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97789): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97804): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97824): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97826): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97828): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97849): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97874): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(97889): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99291): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99321): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99323): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99341): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99356): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99371): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99373): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99396): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99411): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99436): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99456): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99471): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99501): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99521): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99916): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99931): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99956): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99976): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(99991): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100046): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100061): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100076): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100091): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100106): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100121): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100146): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100166): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100168): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100170): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100191): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100195): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100199): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100231): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100266): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100268): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100291): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100306): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100326): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100341): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100356): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100371): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100386): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100401): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100416): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100431): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100446): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100461): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100481): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100501): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100516): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100531): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100533): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100556): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100571): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100586): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100601): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100616): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100711): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100731): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100751): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100753): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100757): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100786): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100788): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100811): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100813): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100815): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100846): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100861): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100891): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100911): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100926): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100941): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100961): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100963): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100965): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(100986): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(101011): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      talib/_ta_lib.c(101026): warning C4146: tek iŸlenenli eksi iŸareti iŸaretsiz t\x81re uyguland\x8d; sonu‡ hala iŸaretsiz
      "C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.43.34808\bin\HostX86\x64\link.exe" /nologo /INCREMENTAL:NO /LTCG /DLL /MANIFEST:EMBED,ID=2 /MANIFESTUAC:NO /LIBPATH:c:\ta-lib\c\lib "/LIBPATH:c:\Program Files\TA-Lib\lib" "/LIBPATH:c:\Program Files (x86)\TA-Lib\lib" "/LIBPATH:C:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.11_3.11.2544.0_x64__qbz5n2kfra8p0\libs" "/LIBPATH:C:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.11_3.11.2544.0_x64__qbz5n2kfra8p0" "/LIBPATH:C:\Program Files\WindowsApps\PythonSoftwareFoundation.Python.3.11_3.11.2544.0_x64__qbz5n2kfra8p0\PCbuild\amd64" "/LIBPATH:C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.43.34808\lib\x64" "/LIBPATH:C:\Program Files (x86)\Windows Kits\10\lib\10.0.22621.0\ucrt\x64" "/LIBPATH:C:\Program Files (x86)\Windows Kits\10\\lib\10.0.22621.0\\um\x64" ta-lib-static.lib /EXPORT:PyInit__ta_lib build\temp.win-amd64-cpython-311\Release\talib\_ta_lib.obj /OUT:build\lib.win-amd64-cpython-311\talib\_ta_lib.cp311-win_amd64.pyd /IMPLIB:build\temp.win-amd64-cpython-311\Release\talib\_ta_lib.cp311-win_amd64.lib
      LINK : fatal error LNK1181: 'ta-lib-static.lib' giriŸ dosyas\x8d a‡\x8dlam\x8dyor
      error: command 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.43.34808\\bin\\HostX86\\x64\\link.exe' failed with exit code 1181
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for TA-Lib
Failed to build TA-Lib
ERROR: Failed to build installable wheels for some pyproject.toml based projects (TA-Lib)
