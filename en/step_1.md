To access a variable from another GameObject, that variable must be public:

--- code ---
---
language: cs
---
public class StarPlayer : MonoBehaviour
{
    public int stars = 0; 
}
--- /code ---

You can then create a variable with the type of the script that has the variable and set it using the Inspector. 

You will then be able to access the variable to read the value or update it. 

--- code ---
---
language: cs
---
    StarPlayer player;

    void AddStar()
    {
        player.stars += 1; // increase by 1
    }
--- /code ---

