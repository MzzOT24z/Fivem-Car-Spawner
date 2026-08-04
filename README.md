Drop the car_spawner folder into your server's resources directory, then add ensure car_spawner to your server.cfg.

Commands:

/car [model] — e.g. /car adder, /car sultan — spawns the vehicle a few meters in front of you and puts you in the driver seat
/dv — deletes the vehicle you're in, or the nearest one you spawned if you're on foot

Notes:

No permission checks — anyone on the server can use these commands. If you want it locked to admins, tell me and I'll add an ACE permission check.
Model names need to be valid GTA V vehicle spawn names (vanilla or added via your server's vehicle add-ons).
It only cleans up vehicles it spawned (tracked in a table), so it won't touch other traffic.
