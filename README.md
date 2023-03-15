# jpn_explainable_qa_dataset

This repository contains the following datasets and script:

- Corpus (`corpus/early_version.json`)
- Crowdsourcing interface (TBA by April)

## Corpus

### File format

The files are in standard JSON format.


```
[
	{
		"_id": "4387156_2",
		"question": "大田区の区の鳥の分類は何目何科でしょうか？",
		"answer": "スズメ目ウグイス科",
		"derivations": [
			[
				"大田区",
				"i_15",
				[
					"大田区",
					"区の鳥",
					"ウグイス"
				]
			],
			[
				"ウグイス",
				"a_19",
				[
					"ウグイス",
					"分類",
					"スズメ目ウグイス科"
				]
			]
		],
		"type": "bridge",
		"level": ""
	},
		{
		"_id": "4257992_0",
		"question": "槇原敬之と草野マサムネは二人とも血液型はO型ですか？",
		"answer": "YES",
		"derivations": [
			[
				"槇原敬之",
				"abstract",
				[
					"槇原敬之",
					"血液型",
					"O型"
				]
			],
			[
				"草野マサムネ",
				"other",
				[
					"草野マサムネ",
					"血液型",
					"O型"
				]
			]
		],
		"type": "comparison",
		"level": ""
	},
```


