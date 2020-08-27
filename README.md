# AER_Line_File

The AER Line File starts with HITRAN parameters, then modifies them with observed parameters (e.g., through radiation closure studies). It is publicly available on [on Zenodo](https://zenodo.org/record/3837550). This repository does **not** contain this database, because it is a very large set of files. Rather, we provide a simple script that leverages the [Zenodo Python API](https://pypi.org/project/zenodo-get/) to download the file. While the user is free to download the Line File on their own, this repository will also serve as reference, since it will contain documentation in this README and in the [Wiki Pages](https://github.com/AER-RC/AER_Line_File/wiki).
