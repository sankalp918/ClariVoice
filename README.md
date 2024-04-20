**Description**: This project is a simplified version of AWS Transcribe. It takes video files and converts them to audio files using FFMPEG. The audio files are then transcribed, and the transcriptions are saved to text files. Additionally, I have implemented a small NLP model which suggests videos based on the user's input keywords and topics. The text files are first normalized before being used in the NLP model.

-----------------------------------------------------------------------------------------------------------------------------

**Prerequisites**: 
  1. Install [FFMPEG](https://ffmpeg.org/download.html).
  2. Install [AWS-CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) (if videos are stored on S3 bucket).

-----------------------------------------------------------------------------------------------------------------------------

**Instructions to run**: The code contains the prerequisite libraries to be installed and will install them automatically. Use Python version 3.11.0.
