# Lahore-Sky SRCNN: Urban Astrophotography Toolkit

A flux-conserving super-resolution pipeline designed for amateur astrophotography in severe light pollution (Bortle 8-9) and high-aerosol environments like Lahore, Pakistan. 

This toolkit uses a physical forward model to simulate atmospheric turbulence, mount tracking errors, and smog extinction for a 130mm telescope. It trains a convolutional neural network (AstroSRCNN) to recover image resolution while mathematically preserving accurate aperture photometry using a custom flux-window constraint.

Designed for grassroots astronomy clubs and educational initiatives to process their own observations using low-cost or recycled hardware.
