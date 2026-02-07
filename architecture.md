## Product Choice
- Product name: Telegram messenger
- Link to the product: https://web.telegram.org/
- Short description: Good product for conversations

- ## Main components
- ![Telegram Component Diagram](diagrams/out/telegram/component-diagram/Component%20Diagram.svg)
-![Telegram Component Diagram_Code](diagrams/out/telegram/component-diagram/Component%20Diagram.svg)
- Descpirtion of 5 components:
- 1. Desktop App for desktop version of Telegram
- 2. Mobile App(IOS/Android) for phone version of phone app
- 3.Bot API serves: goog bot
- 4.Media & File Service: good servicr
- 5. Secret Chat Relay: very secreet
 
6.  Data flow
- ![Telegram Sequence Diagram](diagrams/out/telegram/sequence-diagram/Sequence%Diagram.svg)

- 1. Select Photo & Send: client send photo
  2. RPC: saveFilePart (bytes, file_id_A): file store
  3. Stream File Data: stream data
  4. Write File Chunk: file chunk 
  5. Checksum OK: check if it is ok
     
## Deployment
![Telegram Deployment Diagram]diagrams/out/telegram/deployment-diagram/Deployment Diagram.svg
justification: cool deployment
## Assumptions
I assume the cloud storage system implements deduplication to decrease cost of storage of secreet chat
I assume that we need to change smth with latchs 
## Open questions
How we can protect data?
How we can keep a secret chat only in app mode?

