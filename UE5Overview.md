# Unreal Engine 5 Documentation Overview

This repository focuses on the community-supported HTML5 platform extension for Unreal Engine 4. For Unreal Engine 5, Epic maintains extensive official documentation.

## Getting Started with UE5

The official UE5 documentation provides step-by-step guides for installing the engine, creating projects, and using new features such as Nanite, Lumen, MetaSounds and Chaos physics.

A minimal C++ class example:

```cpp
#include "GameFramework/Actor.h"
#include "MyActor.generated.h"

UCLASS()
class AMyActor : public AActor
{
    GENERATED_BODY()

public:
    AMyActor();

protected:
    virtual void BeginPlay() override;

public:
    virtual void Tick(float DeltaTime) override;
};
```

## Useful Links

- [Official Unreal Engine 5 Documentation](https://docs.unrealengine.com/5.0/en-US/)
- [Blueprint Visual Scripting](https://docs.unrealengine.com/5.0/en-US/Blueprints/)
- [C++ Programming in UE5](https://docs.unrealengine.com/5.0/en-US/ProgrammingAndScripting/ProgrammingWithCPP/)
- [Samples and Tutorials](https://docs.unrealengine.com/5.0/en-US/Community/SampleProjects/)

These resources contain detailed explanations and usage examples for every major feature of the engine.
