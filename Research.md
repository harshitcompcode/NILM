The authors also propose a new signature for NILM that is based on the wavelet transform. The wavelet transform is a mathematical technique that can be used to decompose a signal into its constituent frequency components. The authors argue that the wavelet transform is well-suited for NILM because it can capture the unique frequency signatures of different appliances.

The proposed NILM approach works as follows:

The voltage and current measurements are collected from the distribution system.
The wavelet transform is applied to the voltage and current measurements to extract the wavelet signatures.
The wavelet signatures are fed into the deep learning model to predict the power consumption of individual appliances.

The wavelet transform is a mathematical technique that can be used to decompose a signal into its constituent frequency components. It works by passing the signal through a series of filters, each of which is tuned to a different frequency band. This produces a set of wavelet coefficients, which represent the signal's energy at different frequency bands.

Wavelet signatures are extracted from the voltage and current measurements by applying the wavelet transform to each measurement. The wavelet coefficients are then used to create a signature for each appliance. The signature is a unique representation of the appliance's power consumption pattern.

The wavelet signatures are then fed into the deep learning model. The deep learning model is trained on a dataset of wavelet signatures and the corresponding power consumption measurements. This allows the model to learn the relationship between the wavelet signatures and the power consumption measurements.

Once the deep learning model is trained, it can be used to predict the power consumption of individual appliances from their wavelet signatures. To do this, the model simply takes the wavelet signature of an appliance as input and outputs the predicted power consumption.

The LSTM RNN used in the paper is trained on a dataset of wavelet signatures and the corresponding power consumption measurements. This allows the model to learn the relationship between the wavelet signatures and the power consumption measurements.

Once the LSTM RNN is trained, it can be used to predict the power consumption of individual appliances from their wavelet signatures. To do this, the model simply takes the wavelet signature of an appliance as input and outputs the predicted power consumption.

Here is an example of how wavelet signatures and deep learning can be used to predict the power consumption of an individual appliance:

A homeowner has a smart meter that measures the voltage and current consumption of their home.
>The smart meter sends the voltage and current measurements to a cloud-based NILM system.
>The NILM system uses a wavelet transform to extract the wavelet signatures from the voltage and current measurements.
>The NILM system feeds the wavelet signatures into a deep learning model that has been trained on a dataset of wavelet signatures and the corresponding power consumption measurements.
>The deep learning model predicts the power consumption of the individual appliance based on its wavelet signature.
>The NILM system sends the predicted power consumption measurement to the homeowner's smartphone.
>The homeowner can use the predicted power consumption measurement to identify and reduce energy waste.
