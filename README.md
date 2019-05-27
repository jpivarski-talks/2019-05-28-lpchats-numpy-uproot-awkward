# 2019-05-28-lpchats-numpy-uproot-awkward

Jim's tutorials for LPC HATS:

   * [Scientific Python and Uproot](https://indico.cern.ch/event/814895), May 28, 2019 at Wilson Hall 11th floor Sunrise conference room.
   * [Columnar Analysis Tools](https://indico.cern.ch/event/814100), May 29, 2019 at the same location.

For help, log into the [HATS Mattermost channel](https://mattermost.web.cern.ch/cms-exp/channels/hatslpc-2019).

To participate, either install all of the software on your laptop (with [conda](https://docs.conda.io/en/latest/miniconda.html), an isolated 3.1 GB environment that you can remove with `conda remove --name lpchats2019-uproot-awkward --all`):

```bash
git clone https://github.com/jpivarski/2019-05-28-lpchats-numpy-uproot-awkward.git
cd 2019-05-28-lpchats-numpy-uproot-awkward
conda create -f environment.yml             # create an isolated environment and install everything
conda activate lpchats2019-uproot-awkward   # switch to that environment (maybe "source activate...")
conda install jupyterlab
pip install --no-cache numpythia            # only one example uses numpythia; it's slow to install
jupyter lab                                 # runs on your machine, controlled by your web browser
```

or click below to run everything in the cloud: [![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jpivarski/2019-05-28-lpchats-numpy-uproot-awkward/1.0?urlpath=lab)

_(If installation on your laptop fails, use the cloud option. GPU libraries and numpythia not included.)_
