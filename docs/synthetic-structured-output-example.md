# Synthetic structured-output example

This example shows the shape of an output object that can move between workflow steps. Values are fictional and illustrative.

    {
      "personaAnalysis": {
        "audience": "fictional early-career urban professionals",
        "positioning": "practical weekend culture guide",
        "contentPillars": ["discovery", "how-to", "personal perspective"],
        "tone": "clear and curious",
        "constraints": ["60–90 seconds", "no unsupported claims"]
      },
      "topicPlan": {
        "topic": "A one-day neighborhood route",
        "targetWeek": 1,
        "hook": "A useful route for a short weekend",
        "format": "vertical video"
      },
      "videoScript": {
        "title": "A compact weekend route",
        "durationSeconds": 75,
        "beats": ["hook", "three stops", "practical close"],
        "callToAction": "Save the route for later"
      },
      "productionPlan": {
        "shotList": ["opening street view", "detail shot", "map overlay"],
        "bRoll": ["signage", "food detail", "walking transition"],
        "subtitleFocus": ["location", "time", "cost caveat"]
      },
      "publishingTask": {
        "platform": "fictional demo channel",
        "status": "DRAFT",
        "owner": "creator"
      }
    }

The object is a product contract example, not evidence of a live model or a production API response.