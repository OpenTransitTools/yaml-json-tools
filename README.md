- pip install poetry
- git clone https://github.com/OpenTransitTools/yaml-json-tools.git
- cd yaml-json-tools
- poetry install
- cd data
- ./get_otpui_i18n.sh
- cd ..
- poetry run json2locs
- ls *.json
