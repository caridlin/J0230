# Cloudy3D Simulation

## Step 1

For a Sersic disk with a circular velocity defined by the potential of the galactic halo and the disk, I will generate the line emission surface brightness, velocity when viewed face-on and edge-on. Especially I will include emissions of MgII, [OII], [NeIII], [NeV], [OIII] and H-beta.

The velocity of the disk is as follows.

<img src="disk.png" alt="drawing" width="400"/>

Here are the computed emissions from [OII] and the projected velocities viewed with angles 30 and 80 degrees.
<p float="left">
  <img src="angle30.png" width="420" />
  <img src="angle80.png" width="420" /> 
</p>

## Step 2

Add a galactic wind. We will simplify the wind at the moment as a constant velocity, decreasing density wind in an opening angle $\Phi$.

The density scales as $$n(r) = n_0\frac{r_0^2}{r^2}$$ where $n_0$ is the density at inner radius $r_0$ ($r_0$ is chosen to be 0.3 kpc in our model). 


