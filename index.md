# Distribution Preserving Source Separation with Time Frequency Predictive Models

This is the demonstration page of the paper "Distribution Preserving Source Separation with Time Frequency Predictive Models" with the samples used for the MUSHRA-style listening test.

## Info

### Abstract

We provide an example of a distribution preserving source separation method, which aims at addressing perceptual shortcomings of state-of-the-art methods. Our approach uses unconditioned generative models of signal sources. Reconstruction is achieved by means of mix-consistent sampling from a distribution conditioned on a realization of a mix. The separated signals follow their respective source distributions, which provides an advantage when separation results are evaluated in a listening test.

### Reference

Pedro J. Villasana T., Janusz Klejsa, Lars Villemoes, Per Hedelin  (2023). **Distribution Preserving Source Separation with Time Frequency Predictive Models**.

## MUSHRA items

This section contains the 10 items used in the MUSHRA-style listening tests. We trained the models using the VCTK [1] and Supra [2] datasets. These items were never seen during training.

<html>
<table>

  <tr>
    <th>Item</th>
    <th>Mixture</th>
    <th>Sources</th>
    <th>DPSS</th>
    <th>IRM</th>
    <th>PNF</th>
    <th>Low-pass anchor 3.5kHz</th>
  </tr>

  <tr>
    <td>1</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p237_298_mic2res0_yx139bt6626Lres26_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_298_mic2res0_yx139bt6626Lres26_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_298_mic2res0_yx139bt6626Lres26_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_298_mic2res0_yx139bt6626Lres26_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_298_mic2res0_yx139bt6626Lres26_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_298_mic2res0_yx139bt6626Lres26_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_298_mic2res0_yx139bt6626Lres26_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_298_mic2res0_yx139bt6626Lres26_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_298_mic2res0_yx139bt6626Lres26_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_298_mic2res0_yx139bt6626Lres26_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_298_mic2res0_yx139bt6626Lres26_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>2</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p237_326_mic2res0_zp866tm4852Lres25_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_326_mic2res0_zp866tm4852Lres25_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_326_mic2res0_zp866tm4852Lres25_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_326_mic2res0_zp866tm4852Lres25_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_326_mic2res0_zp866tm4852Lres25_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_326_mic2res0_zp866tm4852Lres25_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_326_mic2res0_zp866tm4852Lres25_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_326_mic2res0_zp866tm4852Lres25_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_326_mic2res0_zp866tm4852Lres25_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p237_326_mic2res0_zp866tm4852Lres25_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p237_326_mic2res0_zp866tm4852Lres25_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>3</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p269_367_mic2res0_zw828tx0197Lres15_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_367_mic2res0_zw828tx0197Lres15_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_367_mic2res0_zw828tx0197Lres15_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_367_mic2res0_zw828tx0197Lres15_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_367_mic2res0_zw828tx0197Lres15_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_367_mic2res0_zw828tx0197Lres15_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_367_mic2res0_zw828tx0197Lres15_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_367_mic2res0_zw828tx0197Lres15_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_367_mic2res0_zw828tx0197Lres15_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_367_mic2res0_zw828tx0197Lres15_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_367_mic2res0_zw828tx0197Lres15_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>4</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p269_371_mic1res0_yt974cv2625Lres79_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_371_mic1res0_yt974cv2625Lres79_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_371_mic1res0_yt974cv2625Lres79_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_371_mic1res0_yt974cv2625Lres79_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_371_mic1res0_yt974cv2625Lres79_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_371_mic1res0_yt974cv2625Lres79_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_371_mic1res0_yt974cv2625Lres79_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_371_mic1res0_yt974cv2625Lres79_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_371_mic1res0_yt974cv2625Lres79_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p269_371_mic1res0_yt974cv2625Lres79_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p269_371_mic1res0_yt974cv2625Lres79_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>5</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p303_329_mic1res0_zt739gs4926Lres89_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_329_mic1res0_zt739gs4926Lres89_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_329_mic1res0_zt739gs4926Lres89_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_329_mic1res0_zt739gs4926Lres89_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_329_mic1res0_zt739gs4926Lres89_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_329_mic1res0_zt739gs4926Lres89_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_329_mic1res0_zt739gs4926Lres89_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_329_mic1res0_zt739gs4926Lres89_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_329_mic1res0_zt739gs4926Lres89_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_329_mic1res0_zt739gs4926Lres89_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_329_mic1res0_zt739gs4926Lres89_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>6</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p303_331_mic1res0_zc118hn1152Lres18_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_331_mic1res0_zc118hn1152Lres18_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_331_mic1res0_zc118hn1152Lres18_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_331_mic1res0_zc118hn1152Lres18_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_331_mic1res0_zc118hn1152Lres18_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_331_mic1res0_zc118hn1152Lres18_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_331_mic1res0_zc118hn1152Lres18_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_331_mic1res0_zc118hn1152Lres18_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_331_mic1res0_zc118hn1152Lres18_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_331_mic1res0_zc118hn1152Lres18_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_331_mic1res0_zc118hn1152Lres18_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>7</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p303_341_mic1res0_ys250pr2232Lres6_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_341_mic1res0_ys250pr2232Lres6_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_341_mic1res0_ys250pr2232Lres6_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_341_mic1res0_ys250pr2232Lres6_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_341_mic1res0_ys250pr2232Lres6_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_341_mic1res0_ys250pr2232Lres6_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_341_mic1res0_ys250pr2232Lres6_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_341_mic1res0_ys250pr2232Lres6_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_341_mic1res0_ys250pr2232Lres6_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p303_341_mic1res0_ys250pr2232Lres6_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p303_341_mic1res0_ys250pr2232Lres6_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>8</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p306_264_mic1res0_zt739gs4926Lres50_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_264_mic1res0_zt739gs4926Lres50_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_264_mic1res0_zt739gs4926Lres50_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_264_mic1res0_zt739gs4926Lres50_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_264_mic1res0_zt739gs4926Lres50_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_264_mic1res0_zt739gs4926Lres50_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_264_mic1res0_zt739gs4926Lres50_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_264_mic1res0_zt739gs4926Lres50_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_264_mic1res0_zt739gs4926Lres50_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_264_mic1res0_zt739gs4926Lres50_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_264_mic1res0_zt739gs4926Lres50_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>9</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p306_277_mic2res0_zk440mh1715Lres4_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_277_mic2res0_zk440mh1715Lres4_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_277_mic2res0_zk440mh1715Lres4_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_277_mic2res0_zk440mh1715Lres4_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_277_mic2res0_zk440mh1715Lres4_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_277_mic2res0_zk440mh1715Lres4_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_277_mic2res0_zk440mh1715Lres4_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_277_mic2res0_zk440mh1715Lres4_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_277_mic2res0_zk440mh1715Lres4_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_277_mic2res0_zk440mh1715Lres4_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_277_mic2res0_zk440mh1715Lres4_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>10</td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/mix/p306_331_mic2res0_yt974cv2625Lres29_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_331_mic2res0_yt974cv2625Lres29_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_331_mic2res0_yt974cv2625Lres29_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_331_mic2res0_yt974cv2625Lres29_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_331_mic2res0_yt974cv2625Lres29_piano_dpss.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_331_mic2res0_yt974cv2625Lres29_speech_irm.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_331_mic2res0_yt974cv2625Lres29_piano_irm.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_331_mic2res0_yt974cv2625Lres29_speech_pnf.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_331_mic2res0_yt974cv2625Lres29_piano_pnf.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./mushra/speech/p306_331_mic2res0_yt974cv2625Lres29_speech_lp35.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./mushra/piano/p306_331_mic2res0_yt974cv2625Lres29_piano_lp35.wav">
        <audio>
      </p>
    </td>
  </tr>

</table>
</html>

## Additional material

### VCTK+MAESTRO

In this section we used the Maestro [3] dataset to train the piano model.

<html>
<table>

  <tr>
    <th>Item</th>
    <th>Mixture</th>
    <th>Sources</th>
    <th>DPSS</th>
  </tr>

  <tr>
    <td>1</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/mix/p237_298_mic2res0_17w2325s027_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p237_298_mic2res0_17w2325s027_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p237_298_mic2res0_17w2325s027_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p237_298_mic2res0_17w2325s027_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p237_298_mic2res0_17w2325s027_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>2</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/mix/p237_326_mic2res0_17w2349s034_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p237_326_mic2res0_17w2349s034_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p237_326_mic2res0_17w2349s034_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p237_326_mic2res0_17w2349s034_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p237_326_mic2res0_17w2349s034_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>3</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/mix/p269_367_mic2res0_17w2291s004_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p269_367_mic2res0_17w2291s004_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p269_367_mic2res0_17w2291s004_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p269_367_mic2res0_17w2291s004_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p269_367_mic2res0_17w2291s004_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>4</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/mix/p269_371_mic1res0_17w2117s013_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p269_371_mic1res0_17w2117s013_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p269_371_mic1res0_17w2117s013_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p269_371_mic1res0_17w2117s013_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p269_371_mic1res0_17w2117s013_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>5</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/mix/p303_329_mic1res0_17w2193s028_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p303_329_mic1res0_17w2193s028_speech.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p303_329_mic1res0_17w2193s028_piano.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/speech/p303_329_mic1res0_17w2193s028_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/vctk_maestro/piano/p303_329_mic1res0_17w2193s028_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

</table>
</html>

### Out-of-distribution mixes

This section contains examples of out-of-distribution mixes. We don't have the original components of these mixtures, nor were the models trained for sources that are present in the mixes.

<html>
<table>

  <tr>
    <th>Item</th>
    <th>Out-of-distribution mixes</th>
    <th>DPSS</th>
  </tr>

  <tr>
    <td>1</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/mix/item1_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/speech/item1_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/real_mixes/piano/item1_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>2</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/mix/item2_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/speech/item2_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/real_mixes/piano/item2_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>3</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/mix/item3_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/speech/item3_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/real_mixes/piano/item3_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>4</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/mix/item4_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/speech/item4_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/real_mixes/piano/item4_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

  <tr>
    <td>5</td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/mix/item5_mix.wav">
        <audio>
      </p>
    </td>
    <td>
      <p>
        <audio controls>
          <source src="./other/real_mixes/speech/item5_speech_dpss.wav">
        <audio>
      </p>
      <p>
        <audio controls>
          <source src="./other/real_mixes/piano/item5_piano_dpss.wav">
        <audio>
      </p>
    </td>
  </tr>

</table>
</html>

## References

<html>
<table>
  <tr>
    <td valign="top">[1]</td>
    <td valign="top">Junichi Yamagishi, Christophe Veaux, Kirsten MacDonald, et al., "CSTR VCTK Corpus: English multi-speaker corpus for CSTR voice cloning toolkit (version 0.92)," University of Edinburgh. The Centre for Speech Technology Research (CSTR), 2019.</td>
  </tr>
  <tr>
    <td valign="top">[2]</td>
    <td valign="top">Zhengshan Shi, Craig Sapp, Kumaran Arul, Jerry McBride, and Julius O Smith III, "SUPRA: Digitizing the Stanford University Piano Roll Archive," in ISMIR, 2019, pp. 517–523.</td>
  </tr>
  <tr>
    <td valign="top">[3]</td>
    <td valign="top">Curtis Hawthorne, Andriy Stasyuk, Adam Roberts, Ian Simon, Cheng-Zhi Anna Huang, Sander Dieleman, Erich Elsen, Jesse Engel, and Douglas Eck. "Enabling Factorized Piano Music Modeling and Generation with the MAESTRO Dataset". In International Conference on Learning Representations, 2019.</td>
  </tr>
</table>
</html>

