{
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": [
                    "keyword.error.logbook",
                    "keyword.warning.logbook",
                    "keyword.info.logbook",
                    "keyword.downtime.logbook",
                    "keyword.log.logbook"
                ],
                "settings": {
                    "foreground": "#FF0000"  // Red for errors
                }
            },
            {
                "scope": [
                    "string.other.timestamp.logbook"
                ],
                "settings": {
                    "foreground": "#008000"  // Green for timestamps
                }
            },
            {
                "scope": [
                    "string.other.engineer.logbook"
                ],
                "settings": {
                    "foreground": "#0000FF"  // Blue for engineer names
                }
            }
            // Add more rules for other keywords as needed
        ]
    }
}
