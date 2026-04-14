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

## 0.7.0 - 2026-4-14

- ***pyproject.toml:*** Confirm support for `Python 3.10` and
`Python 3.14`


- ***pyproject.toml:*** Require a Python version range
of `>=3.10, <3.15`


- **nasa.NASAClient:** Capitalized class and instance attributes
to denote as constants


- **nasa.NASAClient:** Refactored duplicated code for handling
get requests and data retrieval
into the `_get_data` internal class
method


- **nasa.NASAClient:** Updated and cleaned up type
hinting within some class methods


- **nasa.NASAClient:** Cast some overlooked instances of
`int`, `float`, and `bool` to
`str` when being passed as
parameters to GET requests


- **nasa.NASAClient:** Raise `ValueError` rather than `TypeError`
if both `remaining_amount` and `total_amount`
are false when using the
`get_headers` class method, and updated
the method docstring regarding this
exception


- **nasa.NASAClient:** Improved clarity of some possible
exceptions


- **nasa.NASAClient:** Increased the default amount of
time within the `_DEFAULT_RETRY_DELAYS` instance
attribute


- **nasa.NASAClient:** Renamed the `timeout_print` parameter to
`print_timeout_text` and renamed the `_TIMEOUT_PRINT`
instance attribute to `_TIMEOUT_TEXT`


- **nasa.NASAClient:** Fixed a bug where an
empty line would still be
printed if a request timed
out while `print_timeout_text` was false
