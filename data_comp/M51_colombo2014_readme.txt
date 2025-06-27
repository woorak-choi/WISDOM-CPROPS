J/ApJ/784/3     The PAWS catalogs of GMCs and islands in M51    (Colombo+, 2014)
================================================================================
The PdBI Arcsecond Whirlpool Survey (PAWS): environmental dependence of giant
molecular cloud properties in M51.
    Colombo D., Hughes A., Schinnerer E., Meidt S.E., Leroy A.K., Pety J.,
    Dobbs C.L., Garcia-Burillo S., Dumas G., Thompson T.A., Schuster K.F.,
    Kramer C.
   <Astrophys. J., 784, 3 (2014)>
   =2014ApJ...784....3C    (SIMBAD/NED BibCode)
================================================================================
ADC_Keywords: Galaxies, nearby ; Molecular clouds ; Radial velocities ;
              Velocity dispersion ; Interstellar medium ; Carbon monoxide
Keywords: evolution - galaxies: individual (M51, NGC 5194) - galaxies: spiral -
          galaxies: star formation - ISM: clouds - ISM: structure

Abstract:
    Using data from the PdBI Arcsecond Whirlpool Survey (PAWS), we have
    generated the largest extragalactic giant molecular cloud (GMC)
    catalog to date, containing 1507 individual objects. GMCs in the inner
    M51 disk account for only 54% of the total ^12^CO(1-0) luminosity of
    the survey, but on average they exhibit physical properties similar to
    Galactic GMCs. We do not find a strong correlation between the GMC
    size and velocity dispersion, and a simple virial analysis suggests
    that ~30% of GMCs in M51 are unbound. We have analyzed the GMC
    properties within seven dynamically motivated galactic environments,
    finding that GMCs in the spiral arms and in the central region are
    brighter and have higher velocity dispersions than inter-arm clouds.
    Globally, the GMC mass distribution does not follow a simple power-law
    shape. Instead, we find that the shape of the mass distribution varies
    with galactic environment: the distribution is steeper in inter-arm
    region than in the spiral arms, and exhibits a sharp truncation at
    high masses for the nuclear bar region. We propose that the observed
    environmental variations in the GMC properties and mass distributions
    are a consequence of the combined action of large-scale dynamical
    processes and feedback from high-mass star formation. We describe some
    challenges of using existing GMC identification techniques for
    decomposing the ^12^CO(1-0) emission in molecule-rich environments,
    such as M51's inner disk.

Description:
    The Plateau de Bure Interferometer (PdBI) Arcsecond Whirlpool Survey
    (PAWS; Schinnerer et al., 2013ApJ...779...42S) is a large IRAM program
    involving 210hr of observations with the Plateau de Bure
    Interferometer (PdBI) and IRAM 30m telescope to conduct a sensitive,
    high angular resolution (1.16''*0.97''), ^12^CO(1-0) survey of the
    inner disk of M51a (field-of-view, FoV ~270''*170''). The spatial
    resolution at our assumed distance to M51 of 7.6Mpc (Ciardullo et al.
    2002, cat. J/ApJ/577/31) is ~40pc. The inclusion of the 30m single
    dish data during joint deconvolution ensures that flux information on
    all spatial scales is conserved. The rms of the noise fluctuations in
    the cube is ~0.4K per 5km/s channel. This sensitivity is sufficient to
    detect an object with a gas mass of 1.2*10^5^M_{Sun}_ at the
    5{sigma}_rms_ level. The PAWS data cube covers the LSR velocity range
    between 173 and 769km/s. A detailed description of the observing
    strategy, calibration and data reduction is presented by Pety et al.
    (2013ApJ...779...43P).

File Summary:
--------------------------------------------------------------------------------
 FileName    Lrecl    Records    Explanations
--------------------------------------------------------------------------------
ReadMe          80          .    This file
table1.dat     110       1507    PdBI Arcsecond Whirlpool Survey (PAWS) Giant
                                 Molecular Cloud (GMC) catalog
table7.dat     110        309    PdBI Arcsecond Whirlpool Survey (PAWS) island
                                 catalog
--------------------------------------------------------------------------------

See also:
 J/ApJ/772/107  : GMCs in nearby galaxies (Donovan Meyer+, 2013)
 J/A+A/542/A108 : Giant molecular clouds in M33 (Gratier+, 2012)
 J/ApJS/197/16  : CO observations of LMC molecular clouds (MAGMA). (Wong+, 2011)
 J/ApJ/699/1092 : Giant molecular clouds (SRBY) (Heyer+, 2009)
 J/ApJS/178/56  : CO observations of LMC Giant Molecular clouds (Fukui+, 2008)
 J/ApJ/686/948  : CO in extragalactic giant molecular clouds (Bolatto+, 2008)
 J/ApJ/654/240  : Giant molecular clouds in M31 (Rosolowsky+, 2007)
 J/ApJS/149/343 : Giant molecular clouds in M33 (Engargiola+, 2003)
 J/ApJ/577/31   : PNe in six galaxies (Ciardullo+, 2002)
 J/ApJ/551/852  : FCRAO CO survey of the outer Galaxy (Heyer+, 2001)
 J/PASJ/53/971  : CO catalog of LMC molecular clouds (Mizuno+, 2001)

Byte-by-byte Description of file: table[17].dat
--------------------------------------------------------------------------------
   Bytes Format Units     Label Explanations
--------------------------------------------------------------------------------
   1-  4  I4    ---       Seq    [1/1507] Object identification number (1)
   6-  7  I2    h         RAh    Hour of Right Ascension (J2000)
   9- 10  I2    min       RAm    Minute of Right Ascension (J2000)
  12- 16  F5.2  s         RAs    Second of Right Ascension (J2000)
  18- 19  I2    deg       DEd    Degree of Declination (J2000)
  21- 22  I2    arcmin    DEm    Arcminute of Declination (J2000)
  24- 28  F5.2  arcsec    DEs    Arcsecond of Declination (J2000)
  30- 35  F6.1  km/s      Vlsr    [-125.1/132.6] Local standard of rest
                                   radial velocity ({Delta}V_LSR_) (2)
  37- 40  F4.1  K         Tmax   [1.1/16.5] Peak brightness temperature
                                  (T_max_) (3)
  42- 45  F4.1  ---       S/N    [3.5/41.6] Peak Signal-to-Noise ratio
  47- 50  I4    pc        Reff   [5/2346] Effective radius (4)
  52- 54  I3    pc      e_Reff   [0/133] Uncertainty in Reff
  56- 59  F4.1  km/s      sigma  [0.7/50.7] Velocity dispersion ({sigma}_v_) (6)
  61- 64  F4.1  km/s    e_sigma  [0/23.7] Uncertainty in sigma
  66- 71  F6.1  ---       LCO    [0.1/6446.7] The CO luminosity L_CO_
                                  (in 10^5^K.km/s.pc2 units) (7)
  73- 76  F4.1  ---     e_LCO    [0.1/56.5] Uncertainty in LCO
                                  (in 10^5^K.km/s.pc2 units)
  78- 84  F7.1 10+5Msun   Mvir   [0.2/62661.8] Mass inferred from virial theorem
                                  (M_vir_) (8)
  86- 91  F6.1 10+5Msun e_Mvir   [0/1090.1] Uncertainty in Mvir
  93- 97  F5.2  ---       alpha  [0.01/48.5] Virial parameter {alpha} (9)
  99-101  I3    deg       PA     [0/179] Position angle of object major
                                  axis (10)
 103-105  F3.1  ---       b/a    [0.1/5.6] Minor-to-major axis ratio (11)
 107-108  A2    ---       Reg    Region of M51 where a given object has been
                                  identified (CR, SA, or IA) (12)
     110  I1    ---     f_Reff   [0/1] Radius measurement flag (1=upper limit,
                                  0=actual measurement) (5)
--------------------------------------------------------------------------------
Note (1): Islands are connected emission structures inside the working area
     spanning at least one telescope beam area and one velocity channel. Because
     of the high sensitivity of the Plateau de Bure Interferometer (PdBI)
     Arcsecond Whirlpool Survey (PAWS) cube, the island catalog is dominated by
     the presence of a huge central object that contains more than 50% of the
     total flux present in the data cube and more than 70% of the total emission
     contoured by the CPROPS algorithm (Rosolowsky & Leroy, 2006PASP..118..590R)
     island  identification. It embodies almost the whole central region and a
     significant portion of the spiral arms. Excluding this entity, the
     remaining islands are evenly distributed between the spiral arm and
     inter-arm regions, with only a few objects located in the central region.
     Approximately, 70% of the islands are associated with a single Giant
     Molecular Cloud (GMC), the majority of which are located in the inter-arm
     region.
Note (2): With respect to the systematic velocity of M51 (V_LSR_=472 km/s;
     Shetty et al., 2007ApJ...665.1138S).
Note (3): The peak brightness temperature of a GMC is the CO brightness at the
     local maximum within the cloud. It is measured directly from the data,
     i.e., without extrapolation or deconvolution.
Note (4): Deconvolved, extrapolated effective radius. The effective radius of
     the cloud is defined as the radius of a circle that encompasses an area
     equivalent to the projected area of the cloud. See additional details in
     Section 3.2.1.
Note (5): See Section 3.2 for details.
Note (6): Deconvolved, extrapolated velocity dispersion.
Note (7): Integrated and extrapolated CO luminosity.
Note (8): The virial mass depends on the density profile of the cloud. For a
     cloud with a density profile of p{propto}r^-1^ the virial mass is:
     M_vir_[M_{Sun}_]=1040{sigma}_v_^2^Rad, (Eq. (8)),
     where Rad is the cloud radius in parsec, and {sigma}_v_ is the velocity
     dispersion in km/s.
Note (9):
     The dimensionless virial parameter {alpha} has a value of order unity and
     characterizes deviations from the virial theorem applied to a
     non-magnetized cloud with no external pressure and constant density (see
     Bertoldi & McKee, 1992ApJ...395..140B). This parameter quantifies the ratio
     of the cloud's kinetic to gravitational energy, i.e.,

     {alpha}=5{sigma}_v_^2^R_eff_/GM_lum_=1161{sigma}_v_^2^R_eff_/M_lum_ (12),
     * {alpha}~1  = Cloud considered as gravitationally bound and stabilized by
                    internal thermal and turbulent pressure against collapse;
     * {alpha}>>1 = Cloud either externally bound or transient features of the
                    interstellar medium (ISM);
     * {alpha}=2  = Regarded as the threshold between gravitationally bound and
                    unbound object;
     * {alpha}<<1 = If long-lived, cloud must be supported against collapse by
                    something more than its internal turbulent motions, such
                    as the magnetic field.
Note (10): Measured clockwise, i.e., from north through west, with north set to
     PA=0{deg}. See more details in Section 3.2.1.
Note (11): The ratio between the major and minor axis is obtained directly from
     the spatial moments {sigma}_b_(0K) and {sigma}_a_(0K) without conversion
     into their physical quantities. The axis ratio, b/a, parameterizes the
     shape of the cloud:
     b/a=1 = Round cloud;
     b/a<1 = Elongated cloud.
Note (12): The three regions are defined as below:
     CR = Center;
     SA = Spiral arms;
     IA = Inter-arm.
--------------------------------------------------------------------------------

History:
    From electronic version of the journal

================================================================================
(End)                 Prepared by [AAS]; Sylvain Guehenneux [CDS]    08-Aug-2016
