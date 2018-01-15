# schema
A repository for holding schema templates for the ixo Protocol

## Folder Structure
`/projects` - Project Templates

`/agents` - Agent Templates

`/claims` - Claim Templates

`/evaluations` - Evaluation Templates

## Template Schemas
All Templates follow the [JSON-LD](https://developers.google.com/search/docs/guides/intro-structured-data) structure examples can be found at [Schema.org](http://schema.org)

Example:
```
{
  "@context": "http://schema.org",
  "@type": "Organization",
  "url": "http://www.example.com",
  "name": "Unlimited Ball Bearings Corp.",
  "contactPoint": {
    "@type": "ContactPoint",
    "telephone": "+1-401-555-1212",
    "contactType": "Customer service"
  }
}
```
