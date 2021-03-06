<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [BackgroundService](./puppeteer.protocol.backgroundservice.md) &gt; [BackgroundServiceEvent](./puppeteer.protocol.backgroundservice.backgroundserviceevent.md)

## Protocol.BackgroundService.BackgroundServiceEvent interface

<b>Signature:</b>

```typescript
export interface BackgroundServiceEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [eventMetadata](./puppeteer.protocol.backgroundservice.backgroundserviceevent.eventmetadata.md) | [EventMetadata](./puppeteer.protocol.backgroundservice.eventmetadata.md)<!-- -->\[\] | A list of event-specific information. |
|  [eventName](./puppeteer.protocol.backgroundservice.backgroundserviceevent.eventname.md) | string | A description of the event. |
|  [instanceId](./puppeteer.protocol.backgroundservice.backgroundserviceevent.instanceid.md) | string | An identifier that groups related events together. |
|  [origin](./puppeteer.protocol.backgroundservice.backgroundserviceevent.origin.md) | string | The origin this event belongs to. |
|  [service](./puppeteer.protocol.backgroundservice.backgroundserviceevent.service.md) | [ServiceName](./puppeteer.protocol.backgroundservice.servicename.md) | The Background Service this event belongs to. |
|  [serviceWorkerRegistrationId](./puppeteer.protocol.backgroundservice.backgroundserviceevent.serviceworkerregistrationid.md) | [ServiceWorker.RegistrationID](./puppeteer.protocol.serviceworker.registrationid.md) | The Service Worker ID that initiated the event. |
|  [timestamp](./puppeteer.protocol.backgroundservice.backgroundserviceevent.timestamp.md) | [Network.TimeSinceEpoch](./puppeteer.protocol.network.timesinceepoch.md) | Timestamp of the event (in seconds). |

