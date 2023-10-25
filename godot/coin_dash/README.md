# Godot 4 Game Development Projects

## Coin Dash

- under _Stretch_, set _Mode_ to _canvas_items_ and _Aspect_ to _keep_ in _Project/Setting_: ensure that if a user resizes the game window, everything will scale appropriately and not become stretched or deformed.
- uncheck the _Resizable_ box under _Size_ to prevent the window from being resized at all.
- Keeping individual game objects separate from each other makes them easier to troubleshoot, modify, and even replace entirely without affecting other parts of the games.
- _Make selected node's children not selectable_ to avoid resize the children node unexpectly.
- With _Area2D_, you can detect when other objects overlap or run into a player, but _Area2D_ doesn't have an appearance on its own.
- _AnimatedSprite2D_ node will handle the appearance and animations for the player. 