# easy-mcp
An easy mcp demo. Adapt to LLM with openai as interface.

## requirement
- python >= 3.10
- LLM api(openai type)

```
pip install -r requirements.txt
```

## config
firstly, create a `.env` file in the root directory, then copy the following content into the file and modify the corresponding parameters.

```
OPENAI_API_KEY=<your_api_key>
BASE_URL=<your_api_base_url>
MODEL=<your_model_name>
```

## run
Make sure you have completed the above configuration.

```
python mcp_client.py mcp_server.py
```