# Google Search Console properties

This document records the personal website and external publishing properties separately. Search Console properties are independent; verification for one site does not verify another.

## External properties

### Substack

- **Profile:** Promiscus — <https://substack.com/@promiscus>
- **Publication:** Lord of the Loose Arts
- **Canonical URL:** <https://lordloosearts.substack.com/>
- **Google Search Console property:** URL-prefix property `https://lordloosearts.substack.com/`
- **Verification status:** Not confirmed. No Search Console verification for this Substack publication has been completed or recorded here.
- **Notes:** The profile’s publication link and the publication page’s canonical URL both identify `https://lordloosearts.substack.com/`. Add this exact URL as a **URL-prefix** property in Search Console; a Domain property would require control of DNS for `substack.com`, which publication owners do not have. Google’s URL-prefix property includes the protocol and trailing slash. [Google property setup guide](https://support.google.com/webmasters/answer/34592?hl=en)

Substack says that Google Search Console verification and sitemaps are features that become available as a publication grows. If the publication’s Substack settings provide a **Google Site Verification** field, create the URL-prefix property in Search Console, copy the verification value Google gives you into that Substack field, save it, and then select **Verify** in Search Console. If the field is unavailable, Substack has not made that verification option available for this publication; the owner cannot place a verification file or arbitrary HTML tag on the `substack.com` host. Check Substack’s settings again as the publication grows. Do not reuse the personal website’s verification value. [Substack SEO guidance](https://support.substack.com/hc/en-us/articles/4407702258836-How-can-I-optimize-my-Substack-publication-for-SEO)

## Personal website

The personal website remains a separate Search Console property. Its existing verification and Analytics configuration are maintained in `src/site.config.ts`; this document-only change does not alter either setting.
