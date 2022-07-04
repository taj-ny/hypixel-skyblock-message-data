# Hypixel Skyblock message data
This repository contains 227 957 Hypixel Skyblock player messages sent between 27.10.2019 and 2022.02.12. Some messages may actually come from other places (such as the main lobby or TNT run), but their total amount is non-significant.
SkyblockChatFilter's bayesian filtering system was trained on this data.

# Files
- messages.txt (227 957) - all messages 
- normalMessage.txt (101 696) - messages that were not considered spam.
- spamMessages.txt (126 262) - messages that were considered spam.

# Modifications
Usernames have been removed from messages and their order has been shuffled. In some messages, non-ASCII characters have been replaced with question marks due to improper Minecraft configuration. The content of messages hasn't been altered in any other way.

# Spam classification
Spam classification was done using the SkyblockChatFilter mod based on blacklisted words, therefore the quality is not as good as it could be with manual classification.
