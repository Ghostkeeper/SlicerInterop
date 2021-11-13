Slicer Interop
====
This project aims to provide best-effort interoperability between different slicers for 3D printing. That way, if a profile has been created for one slicer, it may reasonably be ported to a different slicer so that it can be used there. The project aims to provide extensions for the most well-known slicers to allow importing the output of other slicers.

Purpose
----
This project aims to achieve three main goals:
* Allow users to broaden their search for good printing profiles. Profiles are the single most influential factor on printing quality, performance and reliability, so allowing selection from profiles that were created for other slicers can improve printed part quality for everyone.
* Make it easier for the creators of printing profiles to distribute their profiles to more users. Not everyone may know of this project or be bothered to use it, but the people creating profiles may use it to help their users.
* Enhance competitiveness between slicers. The hope is that this project will put some pressure on feature parity.

Scope and Disclaimers
----
The focus of this project is to transfer profiles and projects between slicers. If a project contains model data, that model data should be unmodified, even if the output of one slicer is not according to standards. The project does not convert between different 3D modelling formats to allow other slicers to import a file type that it otherwise couldn't.

Not all slicers have the same features. It cannot be expected that a profile created for one slicer will produce the same result when imported to another slicer. While the result of the conversion is hopefully closer to the result produced by the original slicer than if only the model were transferred, it will still not be sufficiently close to directly compare printing quality. There will always be additional effects by behaviour that different slicers implemented differently.

Status and Planning
----
This project is just getting started. The aim is to have a functioning beta version ready for Cura in a few weeks and for Slic3rPE a few weeks after that. Since the main developer is mostly familiar with Cura, help will be needed from the Slic3r community to bring this to fruition.
