<div class="product-roadmap-header">
  <h1>Desktop Roadmap</h1>
  <p>Thunderbird for Windows, macOS, and Linux. Follow the roadmap from active work to future ideas. Timelines may shift as we learn and iterate.</p>
  <p style="font-size: 16px;">Last updated July 23, 2026</p>
  <p><a href="https://www.thunderbird.net/en-US/thunderbird/all/#select-download-desktop">Download Thunderbird for desktop</a></p>
</div>

## <i class="ph ph-pulse"></i> Active
- **Exchange (EWS, GraphAPI)** Finalize the work on the Exchange protocol in order to support all versions of Exchange and Microsoft 365, including calendar and address book support.
- **Global Database** Continue the work on the new Panorama database, allowing users to start testing the new database, and handle a consistent data migration.
- **Improve and extend existing add-ons APIs** Improve the currently available APIs, focus on giving access to new sections and core features, as well as introducing new APIs for specific sections.
- **Encryption and Security Improvements** Improve the support and discovery of OpenPGP and S/MIME, improve email tracking protection, and harden phishing email prevention. These will continue all year as we respond to high priority vulnerabilities, upstream changes, AI-powered sec reports and regressions. (Ongoing maintenance)
- **Settings Interface Improvements** Clean up and reorganize the settings into more discoverable sections and improve its search. User survey will heavily influence the end result.
- **Calendar Dialogs UI/UX** Complete the refresh of the calendar interface and user experience. Some protocols handling changes might be needed.

## <i class="ph ph-calendar-blank"></i> Planned
- **OAuth2 Enhancements** OAuth became a significant initiative due to evolving provider authentication requirements (including PKCE adoption), browser-based authentication improvements, and the need to deliver a seamless Thundermail sign-in experience.


## <i class="ph ph-rocket-launch"></i> Shipped
- **First Time User Experience: Account Hub** Complete Account Hub for all account creations, enable it for first time users. <div class="date-badge">March 2026</div>
- **Unobtrusive Signatures** This was part of the larger “Encryption and Security Improvements” initiative and has been completed to reduce confusion around OpenPGP signatures. <div class="date-badge">March 2026</div>
- **Exchange Email Support**  Full support of email operations and account creation. <div class="date-badge">November 2025</div>
- **Native OS Notifications** Add quick actions to reply, delete, mark messages as read/unread, and manage the notifications. <div class="date-badge">July 2025</div>
- **Implement Glean Telemetry** Move away from the old telemetry implementation and add the new Glean Telemetry. <div class="date-badge">April 2025</div>
- **In-App Notifications** Implement a new notification system that allows the Thunderbird team to push important, time-sensitive information directly to a user's Thunderbird desktop client. <div class="date-badge">May 2025</div>
- **First Time User Experience** We had to refocus on the email onboarding section of the Account Hub due to Exchange, Graph, and Thundermail release. User feedback & telemetry data points at a large percentage of manual config usage, and the new protocols come with very complex manual user flows. First introduction of a 1-click setup OAuth for Thundermail. <div class="date-badge">June 2026</div>
- **System add-on integration** Allowing to ship ad-hoc features faster for objectives that supersede the release train. This will be in 153! <div class="date-badge">June 2026</div>

