# Custom Agent Check Sandbox
Create simple Agent check that collects timing metrics. Agent checks are great way to collect metrics from custom applications or unique systems.

## Configuration
Each check has a YAML configuration file that is placed in the `conf.d` directory. The file name should match the name of the check module (e.g.: checkvalue.py and checkvalue.yaml).

Add files (e.g.: checkvalue.py) for your check in `checks.d` folder, which lives in your Agent root.
