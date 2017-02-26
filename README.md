#ACT Share

- Identification method (requires memory signature updates)
    - Grab playerID from world 
    - POST to ActShare for token
    - Add token to Lodestone Profile
    - ActShare reader
        - Store to ActShare user account -> playerID to player name and server
    - ActShare user joins instance
        - Scan playerID list
        - Sends to ActShare
            - ActShare push notification to mobile user account with playerID
    - Mobile user joins socket room



- Share Link
    - Mode: Public/Private/Unlisted
    - Join socket room
