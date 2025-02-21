# Nyayapath
## AIM: Enhancing Awareness and Accessibility of Digital Legal Platforms in Rural and Underserved Areas

The aim of the project is to Enhancing Awareness and Accessibility of Digital Legal Platforms in Rural and Underserved Areas. Many citizens in rural and underserved areas remain unaware of the existence and benefits of digital legal platforms. This lack of awareness limits their access to timely legal assistance and information, which is crucial for ensuring justice and legal empowerment. The potential of these platforms to bridge the gap in legal services is hindered by insufficient outreach and engagement strategies tailored to these communities.

## Our Solution: AIfication of Awareness and Accessibility

Our solution focuses on training AI on a large legal database rather than being the database ourselves. With our model, the client can ask any legal queries. Our solution will give fun, easy-to-understand story-based simplified answers and other legal information, tips, requirements, etc. Rather than text-to-text replies, our solution focuses on voice-to-voice replies. 

## Current Implementation of the Solution

The current solution implemented takes an audio file and using AST generates a script in their local language. It is then translated into English via NMT. The script is then sent via AI prompt to generate a response, which is again converted to their local language audio via NMT --> TTS. 

## Future Implementation 

There is a provision for backchecking audio files and AI responses, which we are working on to ensure very high accuracy. We are also working on detection of dialect just by hearing the speech.
