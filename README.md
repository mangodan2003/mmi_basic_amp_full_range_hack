# Overview

The MMI Basic audio system installed into many Audi (and probably other) vehicles has an audio amplifier in the rear of the that drives all the speakers.
The audio signal is delivered to it via an optical fibre system (MOST bus).

A problem arises when the original speakers fail and are replaced by alternatives because the system employs an active crossover. The Audio amplifier has a pair of DSPs that break the digital audio signal in to high and low frequency parts. These are fed to a multi channel D-A converter which outputs 4 channels, high and low for left and right. The low part is exceptionally low and too low for replacement components that physically fit (e.g. the popular Focal PS 165F).

These components come with a passive crossover which splits the audio signal at different points and simply installing these into the MMI Basic system as is results in a poor frequency response.

The original "mid range" is designed to cover a far broader part of the audio spectrum than the Focal unit that physically fits in the same place.

# The solution

It should be noted that this is far from ideal, the DSPs in the amplifier more than likely are specifically eq'd to suit the response of the original drivers. That said, this mod results in a far better audio response than is otherwise obtained from a straight swap.
This mod is non destructive and can trivially be reverted if required.

The mod works by re-combining (summing) the outputs of the D-A converters such that the two outputs now both provide the combined (full-range) signal.

WARNING - Never connect the modified amplifier to an original set of component. The low frequency high amplitude signals intended for the woofer will destroy the mid range driver at anything above minimal output signals.


See the image that accompanies this file for details.

The mod is in the form of 2 short lengths of black wire which can be found below and to the right of the ASK logo.
