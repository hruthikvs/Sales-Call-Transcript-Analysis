# Sales Call Analysis using Gemini LLM

A Python-based solution that leverages Google's Gemini LLM to analyze sales call transcripts and evaluate buyers using a structured framework.

## Overview

This project uses Language Models to analyze conversations between sellers and buyers, evaluating the buyer based on a predefined framework. The system provides scores and detailed justifications for:
- Ideal Customer Profile (ICP) Fitment
- Needs & Deal Completion Timing
- Budget & Authority

## Key Features

- Automated analysis of sales call transcripts
- Structured scoring framework (0-2 points per category)
- Detailed justifications for each score
- Support for long-form conversations


## Technical Approach

### 1. Model Initialization
The solution uses Gemini's system instructions feature to establish the context:
```python
sys_instruct = "You are an AI assistant that analyzes sales call transcripts."
```

### 2. Framework Implementation
- Converts evaluation framework into LLM-friendly format
- Uses structured prompts to guide analysis
- Maintains consistent scoring methodology




## Evaluation Framework

The system evaluates three key parameters:
1. **ICP Fitment** (0-2 points)
   - Company size/scale
   - Decision maker status
   - Customer persona match

2. **Needs & Deal Completion** (0-2 points)
   - Pain point clarity
   - Urgency level
   - Implementation timeline

3. **Budget & Authority** (0-2 points)
   - Decision-making power
   - Budget availability
   - Purchase process understanding

Maximum possible score: 6 points (2 points per category)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to Google's Gemini LLM for providing the analysis capabilities
- Framework structure inspired by enterprise sales qualification methodologies
