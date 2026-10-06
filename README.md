# BC Tech Summit 2027 · Fictional event demo

Sample website used as a knowledge source for the Chapter 7 attendee assistant in the Packt book *AI solutions for Dynamics 365 Business Central*. Cronus Events, the venue, dates and practical information are fictional; they are not an event announcement.

## Open the example

```powershell
git clone https://github.com/javiarmesto/bc-tech-summit-2027.git
cd bc-tech-summit-2027
Start-Process .\index.html
```

No build, package installation or Business Central connection is required to read the page. A browser displays the sample agenda, venue, transport, Wi-Fi and catering information.

## Assistant and configuration

`index.html` embeds a Copilot Studio webchat hosted in the author's environment. Its availability, licensing and answers were not tested in this review. Reading the event page does not prove that the assistant is operational. For your own demo, configure and publish your own Copilot Studio agent and replace the iframe destination in your copy; use the page as its knowledge source.

## Files and limits

- [index.html](index.html): static page, styling and embedded assistant.
- `BingSiteAuth.xml`: verification file from the original publication; it is not needed for local reading.
- `README.md`: purpose and local entry point.

The displayed Wi-Fi credentials are fictional sample content. This repository does not query Business Central or supply an AL extension. Static inspection: **6 October 2026**; no browser chat session or deployment validation is claimed. No applicable license file has been confirmed.
