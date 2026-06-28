# Idea for app

The seed idea is to make a natively agent usable backend to enable agents to effectively use spaced-repetition techniques to teach users chosen topics.

## Initial app shape

The polling app that is primarily CLI oriented and uses the AXI guidelines from GitHub kunchenguid/axi

It is a golang app, using the best available spaced-repetition library.

Input data needed should be able to consume available "anki" or other common formats of learning-dictionaries, but I don't think that format allows for rich metadata, such as an animation or other metadata. We should consider a custom, well-defined format to handle this natively, perhaps handling streaming via an adapter for anki format, but having its own format as an optional/enhancement conversion

The concept is that using this tool, the agent could back up its interactive teaching session with the tool's suggestion for content.

