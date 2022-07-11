# life-beyond-our-eyes
people have dreams about seeing aliens but that is difficult, so you can use this simulation and set you're own rules
Here is the sorce code for the simulation under here:
$R = Read-Host -Prompt "Stars in the galaxy."
$fp = Read-Host -Prompt "Planets on stars."
$ne = Read-Host -Prompt "Planets similar to our planet."
$fe = Read-Host -Prompt "Life on planets."
$N = $R*($fp-($ne-$fp))*$fe
Write-Host "The amount of alien-life would be:" $N
