#The Unobtrusive Group Interaction Corpus

Studying group dynamics requires fine-grained spatial and temporal understanding of human behavior. Social psychologists studying human interaction patterns in face-to-face group meetings often find themselves struggling with huge volumes of data that require many hours of tedious manual coding. There are only a few publicly available multi-modal datasets of face-to-face group meetings that enable the development of automated methods to study verbal and non-verbal human behavior.  In this paper, we present a new, publicly available multi-modal dataset for group dynamics study that differs from previous datasets in its use of ceiling-mounted, unobtrusive depth sensors.  These can be used for fine-grained analysis of head and body pose and gestures, without any concerns about participants' privacy or inhibited behavior.  The dataset is complemented by synchronized per-participant audio from lapel microphones, raw transcripts from a speech-to-text algorithm, and manually edited transcripts to correct errors.  The dataset comprises 22 group meetings in which participants perform a standard collaborative group task designed to measure leadership and productivity.  Participants' post-task questionnaires, including demographic information, are also provided as part of the dataset.  In the second half of the paper, we illustrate the results of several multi-modal algorithms we designed to automatically understand audio-visual interactions in the dataset, and present preliminary analyses of perceived leadership, contribution and performance.

The Dataset

The multimodal dataset contains 22 groups performing the Lunar Survival Task Experiment. The Lunar Survival Task is a group collaboration task where the participants discuss a hypothetical survival scenario on the moon and individually rank 15 items in order of importance. After individually ranking the items, the participants must discuss as a group and come to a consensus about the item rankings.
The main features of the dataset are:
1.	22 groups, 86 participants, age groups 18-30 years, different ethnicities, discussions in English.
2.	Group size: 3 – 5 participants.
3.	51 participants self-identified as men, 35 self-identified as women.
4.	Sensing infrastructure: Two ceiling mounted Microsoft Kinects, individual lapel microphones.

How to access 

1.	The dataset is available for download at https://drive.google.com/drive/folders/1PAIXtGZQlj5-h1aBVjs4aQoBwL0HNoN1?usp=sharing
2.	 The folder contains the following subfolders:
  a.	The Lunar Survival Task and post-task answers
    i.	The Lunar Survival Task details
    ii.	The post-task questionnaire
    iii.	The post-task answers and demographics details

  b.	Overhead depth videos
    i.	44 depth videos corresponding to 22 meetings, each video from 1 overhead Kinect.

  c.	 Meeting transcripts
    i.	22 time-stamped, synchronized and anonymized meeting transcripts.

