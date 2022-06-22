### FRBX

Tools for simulating, forecasting and analyzing statistical cross-correlations between fast radio bursts and other cosmological sources.

### DEPENDENCIES

- Python 3.7+
- numpy:    `python3 -m pip install --user numpy==1.19.1`
- scipy:    `python3 -m pip install --user scipy==1.5.2`
- astropy:  `python3 -m pip install --user astropy==3.2.3`
- matplotlib:   `python3 -m pip install --user matplotlib==3.2.1`
- camb: `python3 -m pip install --user --upgrade camb`
- pyfftw:   `python3 -m pip install --user --upgrade pyfftw`
- healpy:   `python3 -m pip install --user healpy==1.14.0`
- h5py:     `python3 -m pip install --user h5py==2.10.0`
- multiprocess: `python3 -m pip install --user --upgrade multiprocess`
- pathos:   `python3 -m pip install --user --upgrade pathos`
- handout:  `python3 -m pip install --user handout==1.1.2`
- corner:   `python3 -m pip install --user corner==2.1.0`
- requests: `python3 -m pip install --user requests==2.24.0`
- chime_frb_api:    `python3 -m pip install --user chime_frb_api==2020.8`
- pymangle: `python3 -m pip install --user pymangle==0.9.1` (gcc-5.4.0)
- pygedm:   `python3 -m pip install --user git+https://github.com/telegraphic/pygedm` (gcc-5.4.0)
- pytz:     `python3 -m pip install --user pytz`

### INSTALLATION

- Define an environment variable `FRBXDATA` pointing to `data`
- `ln -s ARCHIVE_DIR data/archive`, where `ARCHIVE_DIR` can e.g. be `/data/<user_name>`
- `python3 setup.py install --user` (You may also need a `--prefix=` at the end!)
- Follow the [instructions](https://github.com/CHIMEFRB/frb-master/wiki/CHIME-FRB-Authentication#quickstart)
for authenticating access to CHIME/FRB master

### HANDOUTS

We encourage the use of [Python Handouts](https://github.com/danijar/handout) for high-level
scripting and sharing results! Some examples can be found in `./handouts/`. To run one, simply
do `python3 <script_name.py>`. Then, open `data/archive/outputs/<script_name>/index.html` in
your browser!
