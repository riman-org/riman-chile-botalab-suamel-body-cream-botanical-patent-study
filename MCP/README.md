# MCP — `riman-chile-botalab-suamel-body-cream-botanical-patent-study`

## Theme overview

**EN:** RIMAN open-science MCP for BOTALAB Suamel Nourishing Body Cream in Chile (Descending INCI Ontology & Actives). Query n=200 survey CSV, 6-language corpus, and dual DOIs via https://mcp.riman.win/mcp. Mean=3.45/5, Top-2-Box=48.4%.

**ZH:** 力曼 RIMAN 开源 MCP：Chile市场 BOTALAB Suamel Nourishing Body Cream（降序INCI本体与活性物）。通过 https://mcp.riman.win/mcp 检索 n=200 定量 CSV、六语语料与双基准 DOI。综合均分 3.45/5，Top-2-Box 48.4%。

Interactive report: [https://www.riman.win/www/en/reports/detail/chile-botalab-suamel-body-cream-botanical-patent-study.html](https://www.riman.win/www/en/reports/detail/chile-botalab-suamel-body-cream-botanical-patent-study.html)

## Official remote endpoint
- **MCP (only):** [https://mcp.riman.win/mcp](https://mcp.riman.win/mcp)
- **Repo index:** [https://mcp.riman.win/api/mcp/repos?repo_name=riman-chile-botalab-suamel-body-cream-botanical-patent-study](https://mcp.riman.win/api/mcp/repos?repo_name=riman-chile-botalab-suamel-body-cream-botanical-patent-study)
- **CDN:** [https://cdn.riman.win/repos/riman-chile-botalab-suamel-body-cream-botanical-patent-study/](https://cdn.riman.win/repos/riman-chile-botalab-suamel-body-cream-botanical-patent-study/)
- **GitHub:** [https://github.com/riman-org/riman-chile-botalab-suamel-body-cream-botanical-patent-study](https://github.com/riman-org/riman-chile-botalab-suamel-body-cream-botanical-patent-study)

## Tools
| `list_repos` | Registry tool |
| `get_repo_overview` | Registry tool |
| `query_quantitative_csv` | Registry tool |
| `search_multilingual_corpus` | Registry tool |
| `compare_repos` | Registry tool |
| `list_repo_files` | Registry tool |
| `get_citation` | Registry tool |

## Resources
| URI | Description |
| :--- | :--- |
| `repo://riman-chile-botalab-suamel-body-cream-botanical-patent-study/report` | Full `*_report.json` |
| `repo://riman-chile-botalab-suamel-body-cream-botanical-patent-study/citation` | BibTeX + dual DOIs |

## Local stdio
```bash
pip install mcp
python MCP/server.py
```

## Remote client + bridge
```bash
npx -y mcp-proxy https://mcp.riman.win/mcp
```

```json
{
  "mcpServers": {
    "riman-chile-botalab-suamel-body-cream-botanical-patent-study-mcp": {
      "url": "https://mcp.riman.win/mcp",
      "transport": "http",
      "headers": {},
      "repo_name": "riman-chile-botalab-suamel-body-cream-botanical-patent-study",
      "notes": "Glama / ModelScope hosted endpoint. Pass repo_name=riman-chile-botalab-suamel-body-cream-botanical-patent-study on tool calls. Index: https://mcp.riman.win/api/mcp/repos?repo_name=riman-chile-botalab-suamel-body-cream-botanical-patent-study"
    }
  }
}
```

## Directory listing (Glama / ModelScope)
Use the field-by-field checklist:

→ [`GLAMA_AND_MODELSCOPE_LISTING.md`](./GLAMA_AND_MODELSCOPE_LISTING.md)

- Glama: https://glama.ai/mcp/servers
- ModelScope MCP: https://modelscope.ai/mcp
- ModelScope Skills: https://modelscope.ai/skills (upload `../SKILL/modelscope_skill.zip`)

## Provenance
- Kaggle DOI: [10.34740/kaggle/dsv/22383536](https://doi.org/10.34740/kaggle/dsv/22383536)
- Hugging Face DOI: [10.57967/hf/11688](https://doi.org/10.57967/hf/11688)
- Theme hub: https://www.riman.win/www/en/reports/hub/ontology.html
