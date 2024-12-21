# QuestOfMercia
a windows form game


Module Module1

    Public Class Player

        Private name As String
        Public health As Integer
        Private attack1 As Integer
        Private attack2 As Integer

        Public Sub Death()
            Console.WriteLine("God has forsaken me !!!")
        End Sub

        Public Sub Happy()
            Console.WriteLine("I have destroyed your enemies !!!")
        End Sub

        Public Sub BattleCry()
            Console.WriteLine("CHARGE AT THEM MEN !!")
        End Sub

    End Class

    Public Class NPC

        Public health As Integer

    End Class

    Public Class Goblin
        Inherits NPC

        Private slash As Integer
        Private goblinMode As Boolean
        Private bite As Integer

        Public Sub Death()
            Console.WriteLine("THE LIGHT I CAN SEE IT !!")
        End Sub

        Public Sub GoblinModeCall()
            Console.WriteLine("IT'S GOBLIN MODE TIME !!!")
        End Sub

    End Class

    Public Class Wolf
        Inherits NPC

        Private howl As Integer
        Private packInstinct As Boolean
        Private claw As Integer

        Public Sub Death()
            Console.WriteLine("THE HUNT IS OVER...")
        End Sub

        Public Sub WolfMode()
            Console.WriteLine("HOWL!!! THE PACK IS HERE!!!")
        End Sub
    End Class

    Public Class Bear
        Inherits NPC

        Private roar As Integer
        Private hibernate As Boolean
        Private swipe As Integer

        Public Sub Death()
            Console.WriteLine("THE FOREST CALLS ME HOME...")
        End Sub

        Public Sub BearMode()
            Console.WriteLine("ROOOAAAR!!! TIME TO SMASH!!!")
        End Sub
    End Class

    Public Class Dragon
        Inherits NPC

        Private fireBreath As Integer
        Private canFly As Boolean
        Private tailWhip As Integer

        Public Sub Death()
            Console.WriteLine("MY FLAME FLICKERS OUT...")
        End Sub

        Public Sub DragonMode()
            Console.WriteLine("FEEL THE WRATH OF THE SKIES!!!")
        End Sub
    End Class

End Module
