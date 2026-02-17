# Redz-hub
REDZ HUB
game.PlaceId == 2753915549 então
    Mundo1 = verdadeiro
senão se game.PlaceId == 4442272183 então
    Mundo2 = verdadeiro
senão se game.PlaceId == 7449423635 então
    Mundo3 = verdadeiro
outro
    jogo:ObterServiço("Jogadores").JogadorLocal:Expulsar("Não é compatível, aguarde...")
fim

função CheckQuest()
    MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
    se World1 então
        Se MyLevel == 1 ou MyLevel <= 9 então
            Mon = "Bandido"
            LevelQuest = 1
            NameQuest = "BanditQuest1"
            NameMon = "Bandido"
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
            CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
        senão se MyLevel == 10 ou MyLevel <= 14 então
            Mon = "Macaco"
            LevelQuest = 1
