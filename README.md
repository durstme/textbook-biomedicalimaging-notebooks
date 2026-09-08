# PHYS 0241: Biomedical Imaging, Jupyter notebooks

> **Academic use only.** These notebooks are provided for students of PHYS 0241 at
> Middlebury College. Please do not repost or redistribute them. See
> [LICENSE.md](LICENSE.md).

This repository is generated automatically from the course textbook repository;
edits made here are overwritten by the next sync. The rendered notebooks, together
with pre-rendered animations, live on the course textbook site (course password
required): https://durstlab.middcreate.net/teaching/protected/textbook-biomedicalimaging/

## Open a notebook in Google Colab

Click a link in the table below, or use the pattern
`https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/<chNN>/<name>.ipynb`.
In Colab: run the first (setup) cell, then choose **File > Save a copy in Drive** to
keep your changes.

## Run locally

```bash
git clone https://github.com/durstme/textbook-biomedicalimaging-notebooks.git
cd textbook-biomedicalimaging-notebooks
conda env create -f environment.yml && conda activate phys0241   # or: pip install -r requirements.txt
jupyter lab
```

See the "Running the Notebooks" page on the textbook site for more detail.

## Notebooks

| Notebook | Title | |
|---|---|---|
| `ch02/ch02-01.ipynb` | Plane Waves | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch02/ch02-01.ipynb) |
| `ch02/ch02-02.ipynb` | Electromagnetic Wave | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch02/ch02-02.ipynb) |
| `ch02/ch02-03.ipynb` | Plot Gaussian beam radius v. propagation distance $z$ | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch02/ch02-03.ipynb) |
| `ch02/ch02-04.ipynb` | Plane Waves at an Interface -- Refraction | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch02/ch02-04.ipynb) |
| `ch02/ch02-05.ipynb` | Electric field vectors at an interface | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch02/ch02-05.ipynb) |
| `ch02/ch02-06.ipynb` | Fresnel coefficients | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch02/ch02-06.ipynb) |
| `ch03/ch03-01.ipynb` | Ray Tracing | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch03/ch03-01.ipynb) |
| `ch03/ch03-02.ipynb` | Ray Tracing -- Magnification | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch03/ch03-02.ipynb) |
| `ch03/ch03-03.ipynb` | Ray Tracing with Matrices | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch03/ch03-03.ipynb) |
| `ch03/ch03-04.ipynb` | Aberration Simulation | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch03/ch03-04.ipynb) |
| `ch04/ch04-00.ipynb` | Sinusoid Superposition | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-00.ipynb) |
| `ch04/ch04-01.ipynb` | Interference -- Ideal Double Slit | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-01.ipynb) |
| `ch04/ch04-02.ipynb` | Interference - Single Slit | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-02.ipynb) |
| `ch04/ch04-03.ipynb` | Interference - Rectangular Aperture | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-03.ipynb) |
| `ch04/ch04-04.ipynb` | Interference -- Circular Aperture | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-04.ipynb) |
| `ch04/ch04-05.ipynb` | Zeroes of Airy Disk | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-05.ipynb) |
| `ch04/ch04-06.ipynb` | Fraunhofer Diffraction -- Double Slit | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-06.ipynb) |
| `ch04/ch04-07.ipynb` | Fraunhofer Diffraction -- Single Slit | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-07.ipynb) |
| `ch04/ch04-08.ipynb` | Fraunhofer Diffraction -- Rectangular Aperture | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-08.ipynb) |
| `ch04/ch04-09.ipynb` | Fraunhofer Diffraction -- Circular Aperture | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch04/ch04-09.ipynb) |
| `ch05/ch05-01.ipynb` | Fourier Transforms | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-01.ipynb) |
| `ch05/ch05-02.ipynb` | Fourier Transform -- Spatial Frequencies | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-02.ipynb) |
| `ch05/ch05-03.ipynb` | Fourier Transform - Spatial Frequencies 2 | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-03.ipynb) |
| `ch05/ch05-04.ipynb` | Spatial Filtering | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-04.ipynb) |
| `ch05/ch05-05.ipynb` | Convolution | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-05.ipynb) |
| `ch05/ch05-06.ipynb` | Optical Transfer Function | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-06.ipynb) |
| `ch05/ch05-07.ipynb` | Convolution - Calculation with Example Function | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-07.ipynb) |
| `ch05/ch05-08.ipynb` | Convolution - Calculation with Functions (Selectable) | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-08.ipynb) |
| `ch05/ch05-09.ipynb` | Deconvolution | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-09.ipynb) |
| `ch05/ch05-10.ipynb` | Convolution Theorem Approach | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-10.ipynb) |
| `ch05/ch05-11-1D.ipynb` | Optical Imaging: PSF, OTF, Coherent vs. Incoherent | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-11-1D.ipynb) |
| `ch05/ch05-11-2D.ipynb` | Optical Imaging: PSF, OTF, Coherent vs. Incoherent | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-11-2D.ipynb) |
| `ch05/ch05-12.ipynb` | Optical Transfer Function: Modulation | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-12.ipynb) |
| `ch05/ch05-13.ipynb` | Pupil Function, PSF, and OTF | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-13.ipynb) |
| `ch05/ch05-14.ipynb` | Convolution of Two Square Pulses | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-14.ipynb) |
| `ch05/ch05-15.ipynb` | Convolution Theorem: Two Square Pulses | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-15.ipynb) |
| `ch05/ch05-16.ipynb` | The Finite Cosine: Multiplying in Space | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-16.ipynb) |
| `ch05/ch05-17.ipynb` | The Point Spread Function | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-17.ipynb) |
| `ch05/ch05-18.ipynb` | Point Sources, Airy Disks, and Resolution | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-18.ipynb) |
| `ch05/ch05-19.ipynb` | The OTF Acting on a Real Object | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-19.ipynb) |
| `ch05/ch05-20.ipynb` | The Real Double Slit | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-20.ipynb) |
| `ch05/ch05-21.ipynb` | Correlation | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch05/ch05-21.ipynb) |
| `ch08/ch08-01.ipynb` | X-ray projection -- Parallel and Radial | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch08/ch08-01.ipynb) |
| `ch08/ch08-02.ipynb` | X-Ray Projections -- Exact | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch08/ch08-02.ipynb) |
| `ch08/ch08-03.ipynb` | X-Ray Projections | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch08/ch08-03.ipynb) |
| `ch08/ch08-04.ipynb` | X-Ray Radiography -- Geometric Effects | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch08/ch08-04.ipynb) |
| `ch09/ch09-01.ipynb` | Projection | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch09/ch09-01.ipynb) |
| `ch09/ch09-02.ipynb` | Sinogram | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch09/ch09-02.ipynb) |
| `ch09/ch09-03.ipynb` | Backprojection | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch09/ch09-03.ipynb) |
| `ch10/ch10-01.ipynb` | Precession | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch10/ch10-01.ipynb) |
| `ch10/ch10-02.ipynb` | NMR - Free Induction Decay | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch10/ch10-02.ipynb) |
| `ch10/ch10-03.ipynb` | NMR - Spin Echo | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch10/ch10-03.ipynb) |
| `ch10/ch10-04.ipynb` | NMR - Various Pulse Sequences | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch10/ch10-04.ipynb) |
| `ch11/ch11-01.ipynb` | Ultrasound - Phased Array | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch11/ch11-01.ipynb) |
| `ch11/ch11-02.ipynb` | Ultrasound - Phased Array | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/ch11/ch11-02.ipynb) |
| `other/fft_tutorial.ipynb` | `fft` Tutorial | [Open in Colab](https://colab.research.google.com/github/durstme/textbook-biomedicalimaging-notebooks/blob/main/other/fft_tutorial.ipynb) |
