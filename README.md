# Quantitative Single-Neuron Modeling Competition (2009)

## Data Source
This data was used for the 2009 Quantitative Single-Neuron Modeling Competition developed by researchers at EPFL (Ecole Polytechnique Fédérale de Lausanne) in Switzerland. There are four challenges (A-D).  The primary host of the competition is the [INCF](http://www.incf.org/community/competitions/spike-time-prediction/2009).  A Science article about it can be viewed [here](https://doi.org/10.1126/science.1181936).  Experiments to gather data for challenges A and B were performed by Thomas Berger and Richard Naud in the laboratory of Henry Markram at the EPFL. Challenge C experiments were performed by Brice Bathellier and Richard Naud in the lab of Matthew Larkum at the University of Bern. Challenge D experiments are described thoroughly in [Carandini et al. (2007)](https://doi.org/10.1167/7.14.20) and [Sincich et al. (2007)](https://doi.org/10.1523/JNEUROSCI.5077-06.2007).

## Data Summary 
Data for the first three challenges are from Wistar rat cortical neurons.  Data for the last challenge is from rhesus monkey LGN and retinal ganglion cells.

### Challenge A
Contains Wistar rat somatosensory neocortex neuron response to somatic current input. Data consists of 13 repetitions of a 60s-stimulation protocol. Training set is first 39 s, test set is last 21 seconds. Injected current waveform in pA are provided for both training and test phases. Voltage responses are provided for the training but not the test phase.
### Challenge B
Wistar rat layer 5 fast spiking cell responses to somatic current injection. Protocol is similar to challenge A, except that there are only 9 repetitions. Task is to predict the spike timing of a layer 5 fast spiking cell.
### Challenge C
Wistar rat Layer 5 pyramidal cell with both somatic and dendritic input. Task is to predict the timing of somatic spikes of a tufted L5 pyramidal cell responding to in-vivo-like current injected in the apical dendrites and the soma simultaneously. Seven repetitions of a 72 second long input are provided. For each repetition, the first 38 seconds are used for training (current inputs and voltage responses are provided). The last 34 seconds are used for testing (only the inputs are given).
### Challenge D 
Rhesus monkey LGN receiving retinal input. Task is to predict the spike timing of a single post-synaptic neuron in the lateral geniculate nucleus (LGN) given the presynaptic region ganglion cell (RGC) EPSPs inputs. For training (570 seconds of data) both the retinal (pre-synaptic) and geniculate (post-synaptic) spike times are provided. For testing, (190 seconds of data) only the retinal spike times are given.

## Data Format
The data are in text format as described in the crcns-ch-epfl-2009-instructions document.  Sizes for the challenges range from 125k to 25 MB (compressed).

## Data Citation 

If possible publications created through usage of the data should cite the dataset in the following manner:

> Gerstner, W; Naud, R; Carandini, M; Sincich, LC; Horton, JC; Adams, DL; Economides, JR (2009): Quantitative Single-Neuron Modeling Competition for year 2009, developed by researchers at EPFL; data from Wistar rat cortical neurons and rhesus monkey lateral geniculate nucleus and retinal ganglion cells. CRCNS.org.
http://dx.doi.org/10.6080/K0PN93H3

The above citation uses a Digital Object Identifier (DOI) which is assigned to the data set. The DOI was created using DataCite (www.datacite.org) and the California Digital Library, "EZID" system (n2t.net/ezid/).
