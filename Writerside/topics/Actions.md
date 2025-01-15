# Actions

## Execute console command
Runs a console command
<tip>
A list of all commands available in Train Sim World is available on the <a href="https://wiki.trainsimcommunity.com/en/train-sim-world/modding/documentation/ConsoleHelp">Train Sim Community Wiki</a>.
</tip>

### Example 

<code-block lang="json">
{
    "execute": "ts2.dbg.SetCloudiness 1"
}
</code-block>

If the console command was executed successfully, the following response is returned:

<code-block lang="json">
{
    "event": "command_executed"
}
</code-block>

If no response is returned, the syntax is probably incorrect or the command is longer than 1023 characters.