# Generate AI Powered Meeting Notes from your recorded Meet calls

1. Show list of all transcripts via [Google Meet API | Search for all transcripts](https://developers.google.com/meet/api/guides/artifacts#transcripts)
2. On click generate and store MP3 of a specific user chosen transcript
3. Transcribe the mp3 using [@aws-amplify/predictions](https://docs.amplify.aws/react/build-a-backend/add-aws-services/predictions/transcribe-audio/)
4. Use Clause 3 via Amazon Bedrock to generate AI powered meeting notes. Link to examples of how to setup Bedrock in a Amplify Gen 2 app. [Blog](https://aws.amazon.com/blogs/mobile/amplify-gen2-ga/) [repo](https://github.com/aws-samples/recipe-ai/blob/main/amplify/data/bedrock.js)
5. Frontend shows list of completed Meeting Notes jobs.
