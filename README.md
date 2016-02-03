Hello!

1.Transfer the folder "microwave" in the addon folder.

2.In the file "addentities" to replace the microwave and put the pasta with the sauce.


Example:

if not DarkRP.disabledDefaults["modules"]["hungermod"] then
    DarkRP.createEntity("Microwave", {  
        ent = "pr_microwave",
        model = "models/props/cs_office/microwave.mdl",
        max = 1,
        cmd = "buymicrowave",
        allowed = TEAM_COOK
    })
end

Additional features you will find in cfm_config

Don't forget to include hungermod :3
