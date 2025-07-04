# collected-data
Measurement data that has been collected first-hand, that would benefit the community.

That is to say: don't post information you got from somewhere else here.

## What to include
To create a pull-request into this repo (read: to publish data here):

* Create your own directory for the data, unless you are contributing to an existing collection of measurements.
* Create a `README.md` in that directory that explains what the data is and why it's useful to the community (if not obvious).
* Include the measurement meathodology:
  * What measurement equipment was used?  Make and model, where appropriate.  Was is calibrated?
  * Configuration of measurement equipment, device under test, and anything else relevant.  What was connected to what?
  * Any other relevant information that would help a reader understand just what they're looking at.
* Include the data in both raw format, and analyzed format, where appropriate.  For example:
  * Include an image that shows the conclusion quickly: "The SWR at 145MHz is 1.2:1"
  * Include the .s2p file that was used to generate that conclusion, so that others can analyze the data differently: "Sure, but it's entirely reactive. The X=0 point is at 162MHz."  Or whatever.

@SmittyHalibut 2025-07-02
