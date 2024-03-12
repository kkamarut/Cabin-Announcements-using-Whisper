# Introduction

In modern aviation, effective communication between flight crew and passengers is important for ensuring safety, comfort, and overall satisfaction during air travel. However, the clarity and accessibility of captain and flight attendant announcements can sometimes be hindered by various factors such as background noise, accents, or language barriers. To address these challenges and enhance the passenger experience, the project aims to transcribe, translate, and summarize captain and flight attendant announcements.

# Rationale

There are multiple reasons why transcribing captain and flight attendant announcements could be useful and important. Firstly, it ensures clarity and understanding for passengers, particularly in loud environments or for those with hearing impairments. Additionally, providing transcripts enhances accessibility, ensuring that all passengers have access to vital flight information even if they missed or could not hear the announcement.Transcripts can also facilitate language translation and help international travelers gain the same important information.

# Methods

The methods for transcribing captain and flight attendant announcements involve several steps. Firstly, audio recordings of announcements are scrapped from Avsim website These recordings capture a range of scenarios, including routine announcements, safety instructions, and emergency procedures. Next, the audio files are converted into 16 bit wave files and then the Whisper model is used to convert the audio recordings into written text. Later the transcript gets translated from English to Latvian using Deeplr translation tool and summarized using lexRankr package in R. Through these methods, airlines can effectively transcribe captain and flight attendant announcements to improve communication accessibility, compliance, and quality in the aviation industry.

# Findings

After transcribing, translating, and summarizing the audio files of captain and flight attendant announcements, we can see that there are some clear mistakes in the transcription but the overall idea is clear of what the announcement was about. To implement this transcription tool there will need to be additional training done to the Whisper model to minimize any discrepancies or inconsistencies in the text, particularly in emergency situations.
This model is not meant to demonstrate a perfect transcription model but rather introduce a tool that could help passengers catch important information because in the end of the day the transcript, translation, and summary all give at least a bit more information to a person that either could not hear or just missed the announcement all together. 
