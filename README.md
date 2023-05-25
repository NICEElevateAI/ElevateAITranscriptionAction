# ElevateAI Action

This repo is using the Elevate Python SDK for transcription. 

## Usage

Create a secret named api_key with your API key from [ElevateAI](https://www.elevateai.com).

Pass in an input named file. Set this to a URL that is publicly accessible. For testing purposes, you may use this [file and URL](https://app.elevateai.com/_content/ElevateAi.Shared/files/ElevateAI-Audio-Sample.wav).

```yaml
- uses: NICEElevateAI/ElevateAIActions
  with:
    api_key: ${{ secrets.api_key }}
    file: ${{ inputs.file }}
```

