# Frustum

`Frustum` is a term commonly used in the game development industry and is intensely associated with the concept of "culling". It is the field of view of the camera, or more specifically, the portion of the world that is currently visible to your camera in the game. Shaped like a truncated pyramid (or a pyramid with its top cut off), the frustum's small end is where your camera sits, and the larger end is far away from the camera stretching outwards. Objects within this frustum are what the player sees on their screen, and ones outside are not rendered, which helps increase the performance of the game. Frustum culling, thus, is a computational process to determine which objects are within the frustum and should be drawn.