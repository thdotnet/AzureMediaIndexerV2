# AzureMediaIndexerV2
Sample project to demonstrate how to extract subtitles from a video file using Azure Media Indexer Preview 2 from Azure Media Services.

#config.json sample

{
  "version":"1.0",
  "Features":
    [
       {
       "Options": {
            "Formats":["WebVtt","ttml"],
            "Language":"PtBr",
            "Type":"RecoOptions"
       },
       "Type":"SpReco"
    }]
}