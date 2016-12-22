# Migrant
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

Simple SQLite database migrations.

## Usage

The library can be used either as a command line utility:

```bash
migrant migrate database.sqlite migrations_folder/
```

Or as a *Python* library:

```python
import migrant
migrant.migrate('database.sqlite', 'migrations_folder/')
```

## Hacking
You can create a full test database this way:
```bash
./migrant.py migrate test.sqlite test_migrations
```

Running the unit tests:
```bash
python3 -m unittest discover --locals
```

## Download
Install the library from the Python Package Index:
```bash
pip install migrant
```

## License

    Copyright 2016 Sascha Peilicke

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
