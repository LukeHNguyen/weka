C:\Users\lupin>pip install javabridge
Collecting javabridge
  Using cached javabridge-1.0.19.tar.gz (1.3 MB)
  Preparing metadata (setup.py) ... done
Requirement already satisfied: numpy in c:\users\lupin\appdata\local\programs\python\python310\lib\site-packages (from javabridge) (1.23.2)
Building wheels for collected packages: javabridge
  Building wheel for javabridge (setup.py) ... error
  error: subprocess-exited-with-error

  × python setup.py bdist_wheel did not run successfully.
  │ exit code: 1
  ╰─> [1627 lines of output]
      C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\installer.py:27: SetuptoolsDeprecationWarning: setuptools.installer is deprecated. Requirements should be satisfied by a PEP 517 installer.
        warnings.warn(
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('bdist_wheel',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('build',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('build_py',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310\\javabridge',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jutil.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\locate.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\noseplugin.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\wrappers.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\_version.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\__init__.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310\\javabridge\\tests',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_cpython.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_javabridge.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_jutil.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_wrappers.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\__init__.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 160, in build_package_data
          self.mkpath(os.path.dirname(target))
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310\\javabridge\\jars',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\cpython.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\rhino-1.7R4.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\runnablequeue.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\test.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('build_ext',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 188, in run
          self.build_java()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 321, in build_java
          self.build_runnablequeue()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 306, in build_runnablequeue
          self.build_jar_from_single_source(jar, source)
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 301, in build_jar_from_single_source
          self.build_jar_from_sources(jar, [source])
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 230, in build_jar_from_sources
          self.spawn(javac_command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 390, in spawn
          spawn(cmd, search_path, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files\\Java\\jdk1.7.0_80\\bin\\javac.exe" C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\runnablequeue\\RunnableQueue.java'
      Arguments: ()
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 188, in run
          self.build_java()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 322, in build_java
          self.build_test()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 318, in build_test
          self.build_jar_from_single_source(jar, source)
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 301, in build_jar_from_single_source
          self.build_jar_from_sources(jar, [source])
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 230, in build_jar_from_sources
          self.spawn(javac_command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 390, in spawn
          spawn(cmd, search_path, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files\\Java\\jdk1.7.0_80\\bin\\javac.exe" C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\javabridge\\test\\RealRect.java'
      Arguments: ()
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 188, in run
          self.build_java()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 323, in build_java
          self.build_cpython()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 313, in build_cpython
          self.build_jar_from_sources(jar, sources)
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 230, in build_jar_from_sources
          self.spawn(javac_command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 390, in spawn
          spawn(cmd, search_path, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files\\Java\\jdk1.7.0_80\\bin\\javac.exe" C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\javabridge\\CPython.java C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\javabridge\\CPythonInvocationHandler.java'
      Arguments: ()
      Note: C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\java\org\cellprofiler\javabridge\CPythonInvocationHandler.java uses unchecked or unsafe operations.
      Note: Recompile with -Xlint:unchecked for details.
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 522, in build_extension
          log.info("building '%s' extension", ext.name)
      Message: "building '%s' extension"
      Arguments: ('javabridge._javabridge',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 549, in build_extension
          objects = self.compiler.compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 345, in compile
          compile_info = self._setup_compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 354, in _setup_compile
          self.mkpath(os.path.dirname(obj))
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 1013, in mkpath
          mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\temp.win-amd64-cpython-310',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 549, in build_extension
          objects = self.compiler.compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 345, in compile
          compile_info = self._setup_compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 354, in _setup_compile
          self.mkpath(os.path.dirname(obj))
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 1013, in mkpath
          mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\temp.win-amd64-cpython-310\\Release',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\wheel\bdist_wheel.py", line 299, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 549, in build_extension
          objects = self.compiler.compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 421, in compile
          self.spawn(args)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 521, in spawn
          return super().spawn(cmd, env=env)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 1007, in spawn
          spawn(cmd, dry_run=self.dry_run, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.34.31933\\bin\\HostX86\\x64\\cl.exe" /c /nologo /O2 /W3 /GL /DNDEBUG /MD "-IC:\\Program Files\\Java\\jdk1.7.0_80\\include" "-IC:\\Program Files\\Java\\jdk1.7.0_80\\include\\win32" -IC:\\Users\\lupin\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\numpy\\core\\include -IC:\\Users\\lupin\\AppData\\Local\\Programs\\Python\\Python310\\include -IC:\\Users\\lupin\\AppData\\Local\\Programs\\Python\\Python310\\Include "-IC:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.34.31933\\include" "-IC:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Auxiliary\\VS\\include" "-IC:\\Program Files (x86)\\Windows Kits\\10\\include\\10.0.22000.0\\ucrt" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\um" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\shared" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\winrt" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\cppwinrt" "-IC:\\Program Files (x86)\\Windows Kits\\NETFXSDK\\4.8\\include\\um" /Tc_javabridge.c /Fobuild\\temp.win-amd64-cpython-310\\Release\\_javabridge.obj'
      Arguments: ()
      _javabridge.c
      C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\numpy\core\include\numpy\npy_1_7_deprecated_api.h(14) : Warning Msg: Using deprecated NumPy API, disable it with #define NPY_NO_DEPRECATED_API NPY_1_7_API_VERSION
      _javabridge.c(5159): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(5444): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(5668): warning C4311: 'type cast': pointer truncation from 'jclass' to 'int'
      _javabridge.c(6022): warning C4311: 'type cast': pointer truncation from 'jmethodID' to 'int'
      _javabridge.c(6301): warning C4311: 'type cast': pointer truncation from 'jfieldID' to 'int'
      _javabridge.c(6789): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(6978): warning C4244: '=': conversion from 'double' to 'jfloat', possible loss of data
      _javabridge.c(7883): warning C4244: '=': conversion from 'Py_ssize_t' to 'jint', possible loss of data
      _javabridge.c(8122): warning C4013: 'CreateJavaVM' undefined; assuming extern returning int
      _javabridge.c(8513): warning C4244: '=': conversion from 'Py_ssize_t' to 'jint', possible loss of data
      _javabridge.c(9199): warning C4013: 'StopVM' undefined; assuming extern returning int
      _javabridge.c(16069): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(16617): warning C4244: '=': conversion from 'double' to 'jfloat', possible loss of data
      _javabridge.c(18640): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(18916): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(19464): warning C4244: '=': conversion from 'double' to 'jfloat', possible loss of data
      _javabridge.c(20233): warning C4244: '=': conversion from 'Py_ssize_t' to 'jsize', possible loss of data
      _javabridge.c(20700): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(20828): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(22645): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(22911): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23175): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23439): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23703): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23967): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(24231): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(27720): error C2105: '++' needs l-value
      _javabridge.c(27722): error C2105: '--' needs l-value
      _javabridge.c(28308): error C2105: '++' needs l-value
      _javabridge.c(28310): error C2105: '--' needs l-value
      _javabridge.c(29747): warning C4047: 'return': 'int' differs in levels of indirection from 'void *'
      _javabridge.c(30479): warning C4996: '_PyUnicode_get_wstr_length': deprecated in 3.3
      _javabridge.c(30495): warning C4996: '_PyUnicode_get_wstr_length': deprecated in 3.3
      _javabridge.c(32461): warning C4996: 'PyUnicode_FromUnicode': deprecated in 3.3
      error: command 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.34.31933\\bin\\HostX86\\x64\\cl.exe' failed with exit code 2
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for javabridge
  Running setup.py clean for javabridge
Failed to build javabridge
Installing collected packages: javabridge
  Running setup.py install for javabridge ... error
  error: subprocess-exited-with-error

  × Running setup.py install for javabridge did not run successfully.
  │ exit code: 1
  ╰─> [1689 lines of output]
      C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\installer.py:27: SetuptoolsDeprecationWarning: setuptools.installer is deprecated. Requirements should be satisfied by a PEP 517 installer.
        warnings.warn(
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('install',)
      C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py:34: SetuptoolsDeprecationWarning: setup.py install is deprecated. Use build and pip and other standards-based tools.
        warnings.warn(
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('build',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('build_py',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310\\javabridge',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jutil.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\locate.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\noseplugin.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\wrappers.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\_version.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\__init__.py', 'build\\lib.win-amd64-cpython-310\\javabridge')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 350, in build_module
          self.mkpath(dir)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310\\javabridge\\tests',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_cpython.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_javabridge.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_jutil.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\test_wrappers.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 62, in run
          self.build_packages()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 380, in build_packages
          self.build_module(module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 77, in build_module
          outfile, copied = orig.build_py.build_module(self, module, module_file, package)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_py.py", line 351, in build_module
          return self.copy_file(module_file, outfile, preserve_mode=0)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\tests\\__init__.py', 'build\\lib.win-amd64-cpython-310\\javabridge\\tests')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 160, in build_package_data
          self.mkpath(os.path.dirname(target))
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 342, in mkpath
          dir_util.mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\lib.win-amd64-cpython-310\\javabridge\\jars',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\cpython.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\rhino-1.7R4.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\runnablequeue.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 63, in run
          self.build_package_data()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 161, in build_package_data
          _outf, _copied = self.copy_file(srcfile, target)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_py.py", line 50, in copy_file
          return super().copy_file(infile, outfile, preserve_mode, preserve_times,
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 350, in copy_file
          return file_util.copy_file(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\file_util.py", line 137, in copy_file
          log.info("%s %s -> %s", action, src, dir)
      Message: '%s %s -> %s'
      Arguments: ('copying', 'javabridge\\jars\\test.jar', 'build\\lib.win-amd64-cpython-310\\javabridge\\jars')
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 985, in run_command
          log.info("running %s", command)
      Message: 'running %s'
      Arguments: ('build_ext',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 188, in run
          self.build_java()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 321, in build_java
          self.build_runnablequeue()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 306, in build_runnablequeue
          self.build_jar_from_single_source(jar, source)
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 301, in build_jar_from_single_source
          self.build_jar_from_sources(jar, [source])
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 230, in build_jar_from_sources
          self.spawn(javac_command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 390, in spawn
          spawn(cmd, search_path, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files\\Java\\jdk1.7.0_80\\bin\\javac.exe" C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\runnablequeue\\RunnableQueue.java'
      Arguments: ()
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 188, in run
          self.build_java()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 322, in build_java
          self.build_test()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 318, in build_test
          self.build_jar_from_single_source(jar, source)
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 301, in build_jar_from_single_source
          self.build_jar_from_sources(jar, [source])
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 230, in build_jar_from_sources
          self.spawn(javac_command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 390, in spawn
          spawn(cmd, search_path, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files\\Java\\jdk1.7.0_80\\bin\\javac.exe" C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\javabridge\\test\\RealRect.java'
      Arguments: ()
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 188, in run
          self.build_java()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 323, in build_java
          self.build_cpython()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 313, in build_cpython
          self.build_jar_from_sources(jar, sources)
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 230, in build_jar_from_sources
          self.spawn(javac_command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 390, in spawn
          spawn(cmd, search_path, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files\\Java\\jdk1.7.0_80\\bin\\javac.exe" C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\javabridge\\CPython.java C:\\Users\\lupin\\AppData\\Local\\Temp\\pip-install-6mrjsp5b\\javabridge_fd314f176df44652ac5b6f97a6c993ae\\java\\org\\cellprofiler\\javabridge\\CPythonInvocationHandler.java'
      Arguments: ()
      Note: C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\java\org\cellprofiler\javabridge\CPythonInvocationHandler.java uses unchecked or unsafe operations.
      Note: Recompile with -Xlint:unchecked for details.
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 522, in build_extension
          log.info("building '%s' extension", ext.name)
      Message: "building '%s' extension"
      Arguments: ('javabridge._javabridge',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 549, in build_extension
          objects = self.compiler.compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 345, in compile
          compile_info = self._setup_compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 354, in _setup_compile
          self.mkpath(os.path.dirname(obj))
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 1013, in mkpath
          mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\temp.win-amd64-cpython-310',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 549, in build_extension
          objects = self.compiler.compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 345, in compile
          compile_info = self._setup_compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 354, in _setup_compile
          self.mkpath(os.path.dirname(obj))
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 1013, in mkpath
          mkpath(name, mode, dry_run=self.dry_run)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dir_util.py", line 71, in mkpath
          log.info("creating %s", head)
      Message: 'creating %s'
      Arguments: ('build\\temp.win-amd64-cpython-310\\Release',)
      --- Logging error ---
      Traceback (most recent call last):
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\logging\__init__.py", line 1103, in emit
          stream.write(msg + self.terminator)
      ValueError: underlying buffer has been detached
      Call stack:
        File "<string>", line 2, in <module>
        File "<pip-setuptools-caller>", line 34, in <module>
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 382, in <module>
          setup(name="javabridge",
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\__init__.py", line 87, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\install.py", line 68, in run
          return orig.install.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\install.py", line 698, in run
          self.run_command('build')
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build.py", line 132, in run
          self.run_command(cmd_name)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\dist.py", line 1217, in run_command
          super().run_command(command)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\lupin\AppData\Local\Temp\pip-install-6mrjsp5b\javabridge_fd314f176df44652ac5b6f97a6c993ae\setup.py", line 210, in run
          result = _build_ext.run(self, *args, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 84, in run
          _build_ext.run(self)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 346, in run
          self.build_extensions()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 468, in build_extensions
          self._build_extensions_serial()
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 494, in _build_extensions_serial
          self.build_extension(ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\command\build_ext.py", line 246, in build_extension
          _build_ext.build_extension(self, ext)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\command\build_ext.py", line 549, in build_extension
          objects = self.compiler.compile(
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 421, in compile
          self.spawn(args)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\_msvccompiler.py", line 521, in spawn
          return super().spawn(cmd, env=env)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\ccompiler.py", line 1007, in spawn
          spawn(cmd, dry_run=self.dry_run, **kwargs)
        File "C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\_distutils\spawn.py", line 38, in spawn
          log.info(subprocess.list2cmdline(cmd))
      Message: '"C:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.34.31933\\bin\\HostX86\\x64\\cl.exe" /c /nologo /O2 /W3 /GL /DNDEBUG /MD "-IC:\\Program Files\\Java\\jdk1.7.0_80\\include" "-IC:\\Program Files\\Java\\jdk1.7.0_80\\include\\win32" -IC:\\Users\\lupin\\AppData\\Local\\Programs\\Python\\Python310\\lib\\site-packages\\numpy\\core\\include -IC:\\Users\\lupin\\AppData\\Local\\Programs\\Python\\Python310\\include -IC:\\Users\\lupin\\AppData\\Local\\Programs\\Python\\Python310\\Include "-IC:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.34.31933\\include" "-IC:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Auxiliary\\VS\\include" "-IC:\\Program Files (x86)\\Windows Kits\\10\\include\\10.0.22000.0\\ucrt" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\um" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\shared" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\winrt" "-IC:\\Program Files (x86)\\Windows Kits\\10\\\\include\\10.0.22000.0\\\\cppwinrt" "-IC:\\Program Files (x86)\\Windows Kits\\NETFXSDK\\4.8\\include\\um" /Tc_javabridge.c /Fobuild\\temp.win-amd64-cpython-310\\Release\\_javabridge.obj'
      Arguments: ()
      _javabridge.c
      C:\Users\lupin\AppData\Local\Programs\Python\Python310\lib\site-packages\numpy\core\include\numpy\npy_1_7_deprecated_api.h(14) : Warning Msg: Using deprecated NumPy API, disable it with #define NPY_NO_DEPRECATED_API NPY_1_7_API_VERSION
      _javabridge.c(5159): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(5444): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(5668): warning C4311: 'type cast': pointer truncation from 'jclass' to 'int'
      _javabridge.c(6022): warning C4311: 'type cast': pointer truncation from 'jmethodID' to 'int'
      _javabridge.c(6301): warning C4311: 'type cast': pointer truncation from 'jfieldID' to 'int'
      _javabridge.c(6789): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(6978): warning C4244: '=': conversion from 'double' to 'jfloat', possible loss of data
      _javabridge.c(7883): warning C4244: '=': conversion from 'Py_ssize_t' to 'jint', possible loss of data
      _javabridge.c(8122): warning C4013: 'CreateJavaVM' undefined; assuming extern returning int
      _javabridge.c(8513): warning C4244: '=': conversion from 'Py_ssize_t' to 'jint', possible loss of data
      _javabridge.c(9199): warning C4013: 'StopVM' undefined; assuming extern returning int
      _javabridge.c(16069): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(16617): warning C4244: '=': conversion from 'double' to 'jfloat', possible loss of data
      _javabridge.c(18640): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(18916): warning C4244: '=': conversion from 'long' to 'jchar', possible loss of data
      _javabridge.c(19464): warning C4244: '=': conversion from 'double' to 'jfloat', possible loss of data
      _javabridge.c(20233): warning C4244: '=': conversion from 'Py_ssize_t' to 'jsize', possible loss of data
      _javabridge.c(20700): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(20828): warning C4311: 'type cast': pointer truncation from 'jobject' to 'int'
      _javabridge.c(22645): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(22911): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23175): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23439): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23703): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(23967): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(24231): warning C4244: '=': conversion from 'npy_intp' to 'jsize', possible loss of data
      _javabridge.c(27720): error C2105: '++' needs l-value
      _javabridge.c(27722): error C2105: '--' needs l-value
      _javabridge.c(28308): error C2105: '++' needs l-value
      _javabridge.c(28310): error C2105: '--' needs l-value
      _javabridge.c(29747): warning C4047: 'return': 'int' differs in levels of indirection from 'void *'
      _javabridge.c(30479): warning C4996: '_PyUnicode_get_wstr_length': deprecated in 3.3
      _javabridge.c(30495): warning C4996: '_PyUnicode_get_wstr_length': deprecated in 3.3
      _javabridge.c(32461): warning C4996: 'PyUnicode_FromUnicode': deprecated in 3.3
      error: command 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.34.31933\\bin\\HostX86\\x64\\cl.exe' failed with exit code 2
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
error: legacy-install-failure

× Encountered error while trying to install package.
╰─> javabridge

note: This is an issue with the package mentioned above, not pip.
hint: See above for output from the failure.
