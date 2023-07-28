list_libraries - works for debian based distros(depends on dpkg)
list_libraries_rpm - works redhat based distros(depends on rpm)
Requirements - python3, pip3, virtualenv
Steps -
virtualenv .venv

source .venv/bin/actiavte

pip install -r requirements.txt

./list_libraries <path_to_binary> <path_to_xlsx_file>

./list_libraries_rpm <path_to_binary> <path_to_xlsx_file>

Eg:
./list_libraries /usr/bin/vim ~/vim-lib.xlsx

**What list_libraries_rpm does?**

ldd
rpm -qf <path_to_shared_object>
rpm -qi <owner_file>
List package name, version, license, url, summary and description in xlsx file
