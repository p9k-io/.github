# Privacy notice: p9k Gateway Airtable acceptance test

Effective 9 November 2026.

The operator and data controller is **Prokop Simek**, a Czech sole trader,
business identification number (IČO) **88240495**. Contact:
**prokop.simek@p9k.io**. A future p9k company is not the operator of this test.

This notice covers the restricted internal Airtable connector acceptance test.
It does not announce a public or commercial gateway service. Only accounts
explicitly authorized by the operator may participate. Use a separate test base
with synthetic records; do not connect customer data or other people's records.

## What is processed and why

The integration processes the connecting account's identifiers and profile,
the OAuth permissions and credentials needed to reach Airtable, selected base
metadata, synthetic test records, and technical request and security records.
Tool inputs and results may be included in diagnostic logs and acceptance
evidence. Access is limited by the permissions and bases selected during OAuth
authorization and by the gateway's tool policy.

The purpose is to verify connection, account isolation, tool reads and writes,
credential renewal, reconnection and cleanup. The legal basis is the operator's
legitimate interest in developing and securing the integration. Participation
and the grant of account access are voluntary. Do not participate with an
account you are not authorized to connect. No automated decision with legal or
similarly significant effects is made about participants.

## Recipients and protection

Requests pass through the gateway and Airtable's official MCP service. Hosting
and infrastructure providers process the data needed to operate the test.
When a participant invokes a tool from an AI client, that client receives the
requested tool result under its own terms. The integration does not sell data
or use Airtable records to train its own models. OAuth credentials are encrypted
at rest in the gateway and sent over HTTPS; they are not published in test
reports. Reports should contain synthetic data and the minimum technical
metadata needed to verify a result.

Third-party services may process data outside the EEA under their own privacy
terms and transfer arrangements. Review
[Airtable's privacy policy](https://www.airtable.com/company/privacy) and the
privacy terms of the client you choose before connecting. This internal test
does not promise that every third-party processing operation remains in the EEA.

## Retention and withdrawal

Active gateway credentials are retained while the test connection exists and
removed from the active database when it is disconnected. You can revoke the
grant in Airtable and ask the operator to disconnect the gateway connection.
Synthetic records are removed at the end of their bounded test. Diagnostic
records and acceptance evidence are retained only while needed to investigate
outstanding test failures and document acceptance, then removed or anonymized.
Provider trash, backups and provider-side logs follow the provider's retention
rules; disconnecting the gateway does not purge those systems.

## Your rights and contact

Contact **prokop.simek@p9k.io** to request information, access, correction,
erasure, restriction or portability where applicable, or to object to processing
based on legitimate interests. You can also lodge a complaint with a data
protection authority, including the Czech [ÚOOÚ](https://uoou.gov.cz/).
See the [European Commission's explanation of individual rights](https://commission.europa.eu/law/law-topic/data-protection/information-individuals_en).

Any broader release, additional purpose or change of operator requires an
updated notice before it applies. See the [internal test terms](airtable-test-terms.md).
