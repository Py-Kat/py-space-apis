# PySpaceAPIs Changelogs!

## 0.1.0 - 2025-10-03

- This was the Initial Commit!

## 0.2.0 - 2025-10-06

- **nasa.NASAClient:** Added support for all NASA
EONET endpoints


- **nasa.NASAClient:** Rephrased some text and fixed
typos in docstrings

## 0.2.1 - 2025-10-07

- **nasa.NASAClient:** Removed an extra second newline
from HTTP Error messages

## 0.3.0 - 2025-10-10

- **nasa.NASAClient:** Removed the `time_this` decorator
from class methods by default


- **debugtools.time_this:** Moved the `time_this` decorator
into its own importable 'debugtools'
module

## 0.4.0 - 2025-10-11

- ***pyproject.toml:*** Changed PyPI/installation name to `pyspaceapis`
due to a non-existent package
apparently already owning it


- **nasa.NASAClient:** Made errors now raise tracebacks
instead of simply printing an
error message with an empty
dict


- **nasa.NASAClient:** Slightly improved the contents of
some docstrings

## 0.5.0 - 2025-10-20

- **nasa.NASAClient:** Added customizable timeout handling and
refactored error handling method for
easier scalability


- **nasa.NASAClient:** Added the ability to retrieve
Response header data as a
dict


- **nasa.NASAClient:** Updated the type annotation for
the 'api_key' class parameter


- **nasa.NASAClient:** Made the base URLs class
attributes rather than instance
attributes

## 0.6.0 - 2026-1-14

- ***pyproject.toml:*** Changed the package name from
`pyspaceapi` to `pyspaceapis` to avoid
confusion during installation and use


- **nasa.NASAClient:** Corrected the documented maximum number
of requests per API key
