J/A+A/683/A234   Cepheid Metallicity in the Leavitt Law Survey (Bhardwaj+, 2024)
================================================================================
Cepheid Metallicity in the Leavitt Law (C-MetaLL) Survey. V.
New multiband (grizJHKs) Cepheid light curves and period-luminosity relations.
    Bhardwaj A., Ripepi V., Testa V., Molinaro R., Marconi M., De Somma G.,
    Trentin E., Musella I., Storm J., Sicignano T., Catanzaro G.
    <Astron. Astrophys. 683, A234 (2024)>
    =2024A&A...683A.234B        (SIMBAD/NED BibCode)
================================================================================
ADC_Keywords: Stars, variable ; Photometry, SDSS ; Optical
Keywords: techniques: photometric - stars: distances - stars: oscillations -
          stars: variables: Cepheids - Galaxy: general -
          cosmology: distance scale

Abstract:
    The highly debated effect of metallicity on the absolute magnitudes of
    classical Cepheid variables needs to be properly quantified for
    determining accurate and precise distances based on their Leavitt Law.

    Our goal is to obtain homogeneous optical and near-infrared light
    curves of Milky Way Cepheid variables complementing their already
    collected high-resolution spectroscopic metallicities as part of the
    C-MetaLL survey. Together with Gaia parallaxes, we investigate
    period-luminosity-metallicity relations for Cepheid variables at
    multiple wavelengths.

    We present homogeneous multiband (grizJHKs) time-series observations
    of 78 Cepheids including 49 fundamental mode variables and 29
    first-overtone mode variables. These observations were collected
    simultaneously using the ROS2 and REMIR instruments at the Rapid Eye
    Mount telescope.

    The Cepheid sample covers a large range of distances (0.5-19.7kpc)
    with varying precision of parallaxes, and thus astrometry-based
    luminosity fits were used to derive PL and PW relations in optical
    Sloan (griz) and near-infrared (JHKs) filters. These empirically
    calibrated relations exhibit large scatter primarily due to larger
    uncertainties in parallaxes of distant Cepheids, but their slopes
    agree well with those previously determined in the literature. Using
    homogeneous high-resolution spectroscopic metallicities of 61 Cepheids
    covering -1.1<[Fe/H]<0.6dex, we quantified the metallicity dependence
    of PL and PW relations which varies between -0.30+/-0.11 (in Ks) and
    -0.55+/-0.12 (in z) mag/dex in grizJHKs bands. However, the
    metallicity dependence in the residuals of the PL and PW relations is
    predominantly seen for metal-poor stars ([Fe/H]<-0.3dex), which also
    have larger parallax uncertainties. The modest sample size precludes
    us from separating the contribution to the residuals due to parallax
    uncertainties, metallicity effects, and reddening errors. While this
    Cepheid sample is not optimal for calibrating the Leavitt law,
    upcoming photometric and spectroscopic datasets of the C-MetaLL survey
    will allow the accurate derivation of PL and PW relations in the Sloan
    and near-infrared bandpasses, which will be useful for the distance
    measurements in the era of the Vera C. Rubin Observatory's Legacy
    Survey of Space and Time and upcoming extremely large telescopes.

Description:
    Multiband (grizJHKs) time-series observations of 78 Cepheids including
    49 fundamental mode variables and 29 first-overtone mode variables.

File Summary:
--------------------------------------------------------------------------------
 FileName      Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe            80        .   This file
table1.dat       141       78   Pulsation properties of 78 Cepheids
--------------------------------------------------------------------------------

See also:
            I/355 : Gaia DR3 Part 1. Main source (Gaia Collaboration, 2022)
 J/MNRAS/508/4047 : 47 classical Cepheids HARPSN@TNG spectroscopy (Ripepi+ 2021)
 J/A+A/674/A17    : Gaia Data Release 3. The Cepheids sample (Ripepi+, 2023)
 J/A+A/681/A65    : Cepheids PL relation metallicity dependence (Trentin+, 2024)

Byte-by-byte Description of file: table1.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1- 19  I19   ---     GaiaDR3   Gaia DR3 Source ID
      20  A1    ---   n_GaiaDR3   [a] Note on GaiaDR3 (1)
  22- 29  F8.5  d       Per       Pulsation period
  31- 32  A2    ---     Mode      Pulsation mode (FU/FO)
  34- 38  F5.2  mag     gmag      ?=99.90 Intensity-averaged magnitude in g-band
  40- 44  F5.2  mag     rmag      Intensity-averaged magnitude in g-band
  46- 50  F5.2  mag     imag      Intensity-averaged magnitude in i-band
  52- 56  F5.2  mag     zmag      Intensity-averaged magnitude in z-band
  58- 62  F5.2  mag     Jmag      Intensity-averaged magnitude in J-band
  64- 68  F5.2  mag     Hmag      Intensity-averaged magnitude in H-band
  70- 74  F5.2  mag     Kmag      ?=99.9 Intensity-averaged magnitude in K-band
      76  A1    ---     QF        [ABC] Light curve quality flag (2)
  78- 82  F5.2  mag     E(B-V)    ?=99.90 Color-excess E(B-V) from (3)
  84- 88  F5.2  [-]     [Fe/H]    ?=99.90 Metallicities ([Fe/H])
  90- 92  A3    ---     Flag      Source of [Fe/H] (4)
  94- 98  F5.2  mag   e_gmag      ?=99.90 Uncertainty in gmag
 100-103  F4.2  mag   e_rmag      Uncertainty in rmag
 105-108  F4.2  mag   e_imag      Uncertainty in imag
 110-113  F4.2  mag   e_zmag      Uncertainty in zmag
 115-118  F4.2  mag   e_Jmag      Uncertainty in Jmag
 120-123  F4.2  mag   e_Hmag      Uncertainty in Hmag
 125-129  F5.2  mag   e_Kmag      ?=99.9 Uncertainty in Kmag
 131-135  F5.2  mag   e_E(B-V)    ?=99.90 Uncertainty in E(B-V)
 137-141  F5.2  [-]   e_[Fe/H]    ?=99.90 Uncertainty in [Fe/H]
--------------------------------------------------------------------------------
Note (1): : Note as follows:
   a = The seven Cepheids that were not classified as variables in the Gaia DR3
Note (2): Quality flag of the light curve as follows:
   A = best
   B = good
   C = poor
Note (3): From  (Ripepi et al., 2023A&A...674A..17R, Cat. J/A+A/674/A17).
   See Section 2.1 for details.
Note (4): References for metallicities as follows:
   K21 = Kovtyukh et al., 2022MNRAS.510.1894K
   R21 = Ripepi et al., 2021MNRAS.508.4047R, Cat. J/MNRAS/508/4047
   T22 = Trentin et al., 2023MNRAS.519.2331T
   RVS = Recio-Blanco et al., 2023A&A...674A..29R, see Cat. I/355
--------------------------------------------------------------------------------

Acknowledgements:
    Anupam Bhardwaj, anupam.bhardwajj(at)gmail.com

References:
   Bhardwaj et al., Paper I    2023ApJ...955L..13B
   Trentin et al.,  Paper II   2023MNRAS.519.2331T
   Molinaro et al., Paper III  2023MNRAS.520.4154M
   Trentin et al.,  Paper IV   2024A&A...681A..65T, Cat. J/A+A/681/A65

================================================================================
(End)                                        Patricia Vannier [CDS]  19-Mar-2024