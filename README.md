### Analyze insights in audio interview recording with Amazon Transcribe and  Amazon Comprehend
-----
The project aims to design and test a pipeline to analyze a recorded interview with AWS Transcribe and AWS Comprehend Services using Python. The pipeline takes an audio file in WAV format and a text file with a list of reference questions as input. The project leverages AWS Transcribe to get a text transcript from audio and employs the speaker separation function to differentiate between different speakers.

The output from AWS Transcribe is converted into a Pandas DataFrame. The Python difflib package is used to identify reference questions in the interview transcript. The pipeline then identifies interviewee replies to reference questions.

The final steps involve applying AWS Comprehend for sentiment and topic analysis. The Hugging Face library is used to summarize answers.

The project is built with AWS Transcribe and AWS Comprehend services and Python. It provides a complete pipeline that can be easily used to analyze recorded interviews. The project can be used for research purposes or for analyzing interview data in various industries. 
