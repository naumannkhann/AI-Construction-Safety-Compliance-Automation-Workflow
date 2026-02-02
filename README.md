# AI-Construction-Safety-Compliance-Automation-Workflow #
A proof-of-concept AI safety compliance workflow using n8n + Microsoft Azure Computer Vision.

What the system does:
• Automatically analyzes images to detect whether a worker is wearing a safety helmet.
• Applies decision logic to identify safety violations.
• Triggers alerts to supervisors.
• Can log violations for reporting and audits.

How it works:
• Orchestrated using n8n.
• Image analysis powered by Azure Computer Vision.
• Rule-based decision making for compliance checks.

Demo vs Production:
For demonstration purposes, the workflow uses a manual trigger and sample images.
In a production environment, the same architecture can be extended to process live CCTV feeds, video streams, and multiple camera inputs for real-time safety monitoring.

Future enhancements:
• Safety vest detection using Custom Vision.
• Live CCTV / RTSP video integration.
• Automated weekly safety reports.
• Multi-site construction monitoring.
