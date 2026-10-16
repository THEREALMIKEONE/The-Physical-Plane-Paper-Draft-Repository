# The Physical Plane

**A five-coordinate (x, y, z, t, S) mapping of morfs, selectors and replicators**
Mike One · Independent researcher, Italy

- `The_Physical_Plane_Mike_One.pdf` — the paper (11 pages)
- `GM_physical_plane_paper.zip` — the full test suite behind it

The test suite produces 73 labelled results (derivations, pre-set tests, measurements, constraints and diagnostics) on public data: SPARC galaxies, Pantheon+ supernovae, DESI DR2, BOSS, X-COP and kinematic clusters, and four high-redshift galaxy samples.

To rerun everything:

    unzip GM_physical_plane_paper.zip
    cd GM_physical_plane_paper
    pip install -r requirements.txt
    python run_all.py

Data download automatically on the first run. Results are written to `results/paper_results.json`.

I thank Dr Monjo for being the first to run the test suite and for comments on the redshift test and the plasma term along with noticing the bug for Windows porting.
