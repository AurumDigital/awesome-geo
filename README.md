# Awesome GEO

A curated list of resources on **Generative Engine Optimization (GEO)**: how AI assistants and AI search features find, understand, mention and cite brands, and what site owners can do about it.

Maintained by [Aurum Digital](https://aurumdigital.org). Contributions welcome, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Foundations](#foundations)
- [Official documentation: search engines](#official-documentation-search-engines)
- [Official documentation: AI crawlers](#official-documentation-ai-crawlers)
- [Structured data and entities](#structured-data-and-entities)
- [llms.txt](#llmstxt)
- [Indexing and discovery](#indexing-and-discovery)
- [Free tools](#free-tools)
- [Measuring visibility in AI answers](#measuring-visibility-in-ai-answers)
- [Glossary](#glossary)

## Foundations

- [GEO: Generative Engine Optimization](https://arxiv.org/abs/2311.09735) - The 2023 research paper (Aggarwal et al.) that introduced the term and tested methods for improving visibility in generated answers.
- [What is Generative Engine Optimization?](https://aurumdigital.org/insights/what-is-generative-engine-optimization/) - A practical guide for brands: how AI answers are built, GEO vs SEO, and where to start.

## Official documentation: search engines

- [AI features and your website](https://developers.google.com/search/docs/appearance/ai-features) - Google's guidance on AI Overviews and AI Mode. The same SEO best practices apply; no special optimization is required.
- [Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content) - Google's guidance on content quality.
- [Bing Webmaster Guidelines](https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a) - How Bing discovers, crawls and ranks content. Bing results also feed several AI assistants.

## Official documentation: AI crawlers

- [Overview of Google crawlers and fetchers](https://developers.google.com/search/docs/crawling-indexing/overview-google-crawlers) - Includes Google-Extended, the token that controls use of content for Gemini models.
- [OpenAI crawlers](https://platform.openai.com/docs/bots) - GPTBot, OAI-SearchBot and ChatGPT-User, and how to control them in robots.txt.
- [Anthropic crawlers](https://support.claude.com/en/articles/8896518) - ClaudeBot and Anthropic's other user agents, and how site owners can block them.
- [Perplexity crawlers](https://docs.perplexity.ai/guides/bots) - PerplexityBot and Perplexity-User.

## Structured data and entities

- [Schema.org Organization](https://schema.org/Organization) - The vocabulary for describing a company, including `sameAs` links to official profiles.
- [Schema Markup Validator](https://validator.schema.org/) - Validate any schema.org markup.
- [Rich Results Test](https://search.google.com/test/rich-results) - Check which Google rich results a page is eligible for.
- [Wikidata](https://www.wikidata.org/) - The open knowledge base many systems use to resolve entities.

## llms.txt

- [The /llms.txt proposal](https://llmstxt.org/) - The specification for a Markdown file that summarizes a site for language models. A community proposal, not an official standard.
- [llms-txt-generator](https://github.com/AurumDigital/llms-txt-generator) - Open-source, single-file generator ([hosted version](https://aurumdigital.org/tools/llms-txt-generator/)).

## Indexing and discovery

- [IndexNow](https://www.indexnow.org/) - A protocol to notify participating search engines (including Bing) when content changes.

## Free tools

- [llms.txt generator](https://aurumdigital.org/tools/llms-txt-generator/) - Create a correctly formatted llms.txt file in the browser.
- [Organization schema generator](https://aurumdigital.org/tools/organization-schema-generator/) - Build Organization JSON-LD with sameAs profiles.
- [GEO and SEO diagrams](https://aurumdigital.org/resources/geo-diagrams/) - Embeddable diagrams under CC BY 4.0.

## Measuring visibility in AI answers

- [geo-prompt-templates](https://github.com/AurumDigital/geo-prompt-templates) - Buyer-intent prompt templates and a tracking sheet for measuring share of answers across AI platforms.

## Glossary

- [SEO and GEO glossary](https://aurumdigital.org/glossary/) - Plain-English definitions of AI search terms.

## License

Content in this repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit Aurum Digital with a link to https://aurumdigital.org.
