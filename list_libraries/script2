#!/bin/bash

binary_name="contrail-query-engine"
echo "Getting dependencies for ${binary_name} binary"
python3 -m venv python3-virtualenv
source python3-virtualenv/bin/activate
cd timesavers/list_libraries/
pip install -r requirements.txt
./list_libraries_rpm /usr/bin/${binary_name} ${binary_name}.xlsx
