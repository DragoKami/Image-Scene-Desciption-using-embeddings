# Image-Scene-Desciption-using-embeddings

This notebook demonstates end-to-end process of generating image embeddings from Flickr8k dataset using InceptionV3 and generate captions using LSTM.

### Data description

The image captions are released under a CreativeCommons Attribution-ShareAlike license.

Update Oct 28, 2013: In order to request a copy of the dataset, or to see our recent publication on using this dataset for annotation and search, please see:
Framing image description as a ranking task...

M. Hodosh, P. Young and J. Hockenmaier (2013) "Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics", Journal of Artificial Intelligence Research, Volume 47, pages 853-899
If you use this corpus, please cite:

Cyrus Rashtchian, Peter Young, Micah Hodosh, and Julia Hockenmaier. Collecting Image Annotations Using Amazon's Mechanical Turk. In Proceedings of the NAACL HLT 2010 Workshop on Creating Speech and Language Data with Amazon's Mechanical Turk.

Examples:

    <img src='http://www.flickr.com/photos/suzukiman/1305564994/'>
    A man in street racer armor is examining the tire of another racers motor bike.
    The two racers drove the white bike down the road.
    Two motorists are riding along on their vehicle that is oddly designed and colored.
    Two people are in a small race car driving by a green hill.
    Two people in racing uniforms in a street car.

    http://www.flickr.com/photos/jaimemoreno/1351764581/
    A firefighter extinguishes a fire under the hood of a car.
    a fireman spraying water into the hood of small white car on a jack
    A fireman sprays inside the open hood of small white car, on a jack.
    A fireman using a firehose on a car engine that is up on a carjack.
    Firefighter uses water to extinguish a car that was on fire.