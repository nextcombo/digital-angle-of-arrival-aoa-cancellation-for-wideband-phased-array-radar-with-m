# Digital Angle-of-Arrival (AoA) Cancellation for Wideband Phased Array Radar [with MATLAB Code]

Due to the influence of the aperture transit effect, traditional narrow-band beamforming methods cannot be directly applied to wide-band signal beamforming. Therefore, it is necessary to study the beamforming structure for wide-band signals based on the characteristics of wide-band signals. Since the time delay for different frequencies by the array elements is the same, delay units can be used instead of phase shifters to compensate for the time difference of signal arrival at different elements, thus aligning the main lobe direction towards the desired direction. Therefore, using delay units in wide-band phased array radars can achieve better system performance.
Section 2.1 introduces the signal reception model of narrow-band phased array radar as a basis; section 2.2 discusses the received signal model of phased array radar when the signal is a wide-band signal and the commonly used wide-band signal source—the LFM signal model; due to the influence of the aperture transit effect [37], phase shifters cannot control the beam pointing of wide-band phased array radars. To solve the problem of beam forming in wide-band phased array radars, section 2.3.2 analyzes the principle of using delay units to achieve wide-band signal beamforming and the principle of fractional time delay filters in section 2.3.4. Finally, section 2.3.4 introduces the beamforming structure based on fractional time delay filters.
Assuming the echo signal is a narrow-band signal, since the target is far enough from the radar array, the echo signal arriving at the array can be approximated as a plane wave. In the following calculations, first select a reference element, usually the first element as the reference element, which receives the echo signal can be expressed as:
The process of de-skew involves a mixing process, which is particularly characterized by utilizing the characteristics of LFM signals. When two LFM signals have the same modulation slope, after mixing and filtering, a narrow-band single frequency sinusoidal signal will be obtained, whose frequency is determined by the time offset between the two LFM signals. In the radar system, the time offset between two LFM signals is determined by the target distance, so it can be considered that the frequency of the sinusoidal signal is determined by the target distance. By analyzing the output signal spectrum through FFT, the target distance information can be obtained.
The following will explain the principle of de-slope processing through a single-channel receiving process. The diagram of the single-channel de-slope processing block is shown in Figure 5-1.
MATLAB Simulation Results
Referenced literature [1] Niu Yang. Research and implementation of digital technology for broadband phased array radar [D]. Beijing Institute of Technology, 2015.

## Images

![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](01.jpg)
![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](02.jpg)
![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](03.jpg)
![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](04.jpg)
![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](05.jpg)
![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](06.jpg)
![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](07.jpg)
![[Phased Array] Digital Angle-of-Arrival of Wideband Phased Array Radar [with MATLAB Code]](08.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
