J/A+A/542/A108      Giant molecular clouds in M33            (Gratier+, 2012)
================================================================================
Giant molecular clouds in the Local Group galaxy M33.
    Gratier P., Braine J., Rodriguez-Fernandez N.J., Schuster K.F., Kramer C.,
    Corbelli E., Combes F., Brouillet N., van der Werf P.P., Rollig M.R.
   <Astron. Astrophys. 542, A108 (2012)>
   =2012A&A...542A.108G
================================================================================
ADC_Keywords: Galaxies, nearby ; Molecular clouds
Keywords: ISM: clouds - stars: formation - galaxies: evolution - galaxies: ISM -
          Local Group - galaxies: individual: M33 -

Abstract:
    We present an analysis of a systematic CO(2-1) survey at 12"
    resolution covering most of the Local Group spiral M33, which, at a
    distance of 840kpc, is close enough for individual giant molecular
    clouds (GMCs) to be identified. The goal of this work is to study the
    properties of the GMCs in this subsolar metallicity galaxy. The CPROPS
    (Cloud PROPertieS) algorithm was used to identify 337 GMCs in M33, the
    largest sample to date for an external galaxy. The sample is used to
    study the GMC luminosity function, or mass spectrum under the
    assumption of a constant N(H_2_)/I_CO_ ratio.

Description:
    This study is based on CO(2-1) observations of M33 by the IRAM 30m
    telescope. The dataset and data reduction are presented in detail in
    Paper I, Gratier et al., 2010A&A...522A...3G.

File Summary:
--------------------------------------------------------------------------------
 FileName   Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe         80        .   This file
tablea1.dat    89      337   Clouds detected in CO
--------------------------------------------------------------------------------

See also:
    J/A+A/522/A3 : M33 CO(2-1) and HI integrated intensity maps (Gratier+, 2010)

Byte-by-byte Description of file: tablea1.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label    Explanations
--------------------------------------------------------------------------------
   1-  3  I3    ---     GMC      [1/337] Giant Molecular Cloud sequential number
   5-  8  F4.1  ---     PSNR     Peak signal-to-noise ratio
  11- 14  I4    arcsec  oRA      Offset in right ascension (1)
  16- 20  I5    arcsec  oDE      Offset in declination (1)
  22- 25  F4.1  kpc     Rdist    Deprojected distance from the centre of M33
  27- 29  I3    pc      Re       ?=- Effective radius of the cloud
  31- 32  I2    pc    e_Re       ?=- rms uncertainty on Re
  34- 39  F6.1  km/s    VCO      Velocity of the GMC (2)
  41- 44  F4.1  km/s    W(CO)    Linewidth (FWHM) of the GMC (2)
  46- 48  F3.1  km/s  e_W(CO)    rms uncertainty on W(CO)  
  50- 53  F4.1  km/s    W(HI)    FWHM of the HI emission within the sky
                                  projected cloud contour
  55- 58  F4.1  km/s  e_W(HI)    rms uncertainty on W(HI)
  60- 66  E7.2  Msun    MH2      Molecular gas mass
  68- 74  E7.2  Msun  e_MH2      rms uncertainty on MH2
  76- 82  E7.2  Msun    MHI      Atomic gas mass
  84- 89  E6.2  Msun  e_MHI      rms uncertainty on MHI
--------------------------------------------------------------------------------
Note (1): Intensity-weighted central position expressed as an offset with
     respect to the central position of M33: 01:33:50.905+30:39:35.79
Note (2): determined by a Gaussian fit to the line profile with no attempt
     to correct for finite channel width.
--------------------------------------------------------------------------------

History:
    From electronic version of the journal

================================================================================
(End)                                        Patricia Vannier [CDS]  13-Mar-2012
