# Codefast Day 18 · Certificate Generator

## Mission
- Generate personalized course completion certificates via PDFKit and edge functions.
- Support localization, custom branding, and secure share links.

## Implementation Checklist
1. Design certificate layout from Figma tokens and convert to PDFKit drawing commands.
2. Deploy edge function to generate PDFs on demand, caching signed URLs in Supabase.
3. Provide management UI for manual issuance, revocation, and re-send emails.
4. Log issuance events, attach RUM telemetry for download success/failure, and sync to CRM.

## Telemetry & QA
- Validate PDF rendering with snapshot tests and compare to golden images.
- Monitor generation latency and error rates in Datadog.

## Deliverables
- README documenting environment setup, branding overrides, and distribution workflow.
- Checklist for verifying new certificate designs.
