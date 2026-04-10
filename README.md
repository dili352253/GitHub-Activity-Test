# GitHub-Activity-Test
# GitHub-Activity-Test
# GitHub-Activity-Test
install.packages("ggplot2")
library(ggplot2)

# Install
if (!require("devtools")) install.packages("devtools")
devtools::install_github("IMNMV/ClaudeR")

# Set up your AI tool
library(ClaudeR)
install_clauder()          # For Claude Desktop / Cursor
install_cli(tools = "claude")  # For Claude Code CLI

# Start the server in RStudio
claudeAddin()

hist(c(1, 1, 2, 3, 5, 8))

