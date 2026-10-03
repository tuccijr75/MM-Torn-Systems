# MM Torn Systems — Security & Data Promise

This is the public security policy for custom Torn work.

## Credentials

MM Torn Systems will **never ask for your Torn password**.

When a tool needs a Torn API key, the required access is explained before delivery. The tool should request only the permission needed for the agreed feature set.

Complete API keys are not published, logged into public diagnostics, or included in public portfolio material.

## Storage

Local browser/userscript storage is preferred whenever remote infrastructure is unnecessary.

If a project genuinely requires remote storage or a server-side component, that is disclosed before implementation, including:

- what data leaves the browser;
- why it is required;
- where it is stored;
- who can access it;
- how it can be removed or rotated.

## Private data

Customer records, faction information, member/equipment data, private reports, internal thresholds, notes, and other non-public operational information are treated as private.

Public screenshots and case studies use sanitized/demo data unless the customer has explicitly approved another form of publication.

## Torn compliance

Tools are designed around Torn's scripting/API rules.

MM Torn Systems does not offer:

- CAPTCHA bypasses;
- hidden malicious functionality;
- automated non-API Torn requests;
- prohibited background scraping of Torn pages;
- undisclosed API-key use.

When a requested feature has an uncertain compliance boundary, it is reviewed before shipping rather than hidden inside the implementation.

## Key lifecycle

Where applicable, delivered tools support understandable key handling:

1. explain the required permission;
2. validate access;
3. avoid displaying the complete key after save;
4. allow replacement/deletion;
5. handle invalid, paused, disabled, or insufficient-access conditions without uncontrolled retry loops;
6. recommend revocation when a tool is decommissioned.

## Customer visibility

A customer should be able to answer these questions before relying on the delivered tool:

- What data does it read?
- Why does it need that data?
- Where is the data stored?
- Does anything leave the browser?
- Who can see it?
- What happens when access fails?
- How is the tool updated or removed?

Security and data handling are part of the project scope, not an afterthought.
