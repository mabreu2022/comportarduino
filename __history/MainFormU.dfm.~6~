object Form1: TForm1
  Left = 0
  Top = 0
  Caption = 'Form1'
  ClientHeight = 569
  ClientWidth = 566
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'Tahoma'
  Font.Style = []
  OldCreateOrder = False
  OnDestroy = FormDestroy
  OnShow = FormShow
  PixelsPerInch = 96
  TextHeight = 13
  object Label1: TLabel
    Left = 24
    Top = 24
    Width = 249
    Height = 33
    Caption = 'Arduino Leb BLinking'
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -27
    Font.Name = 'Tahoma'
    Font.Style = []
    ParentFont = False
  end
  object ComLed1: TComLed
    Left = 472
    Top = 37
    Width = 25
    Height = 25
    ComPort = ComPort1
    LedSignal = lsConn
    Kind = lkGreenLight
  end
  object btnSetup: TButton
    Left = 40
    Top = 88
    Width = 97
    Height = 25
    Caption = 'Comport Setup'
    TabOrder = 0
    OnClick = btnSetupClick
  end
  object btnConnection: TButton
    Left = 176
    Top = 88
    Width = 75
    Height = 25
    Caption = 'Open'
    TabOrder = 1
    OnClick = btnConnectionClick
  end
  object blinkSwitch: TToggleSwitch
    Left = 328
    Top = 37
    Width = 72
    Height = 20
    TabOrder = 2
    OnClick = blinkSwitchClick
  end
  object ComTerminal1: TComTerminal
    Left = 24
    Top = 136
    Width = 497
    Height = 250
    Color = clBlack
    ComPort = ComPort1
    Emulation = teVT100orANSI
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWhite
    Font.Height = -12
    Font.Name = 'Fixedsys'
    Font.Style = []
    ScrollBars = ssBoth
    TabOrder = 3
  end
  object Button1: TButton
    Left = 24
    Top = 408
    Width = 75
    Height = 25
    Caption = 'Desligar'
    TabOrder = 4
    OnClick = Button1Click
  end
  object Button2: TButton
    Left = 176
    Top = 408
    Width = 75
    Height = 25
    Caption = 'Ligar'
    TabOrder = 5
    OnClick = Button2Click
  end
  object ComPort1: TComPort
    Connected = True
    BaudRate = br9600
    Port = 'COM6'
    Parity.Bits = prNone
    StopBits = sbOneStopBit
    DataBits = dbEight
    Events = [evRxChar, evTxEmpty, evRxFlag, evRing, evBreak, evCTS, evDSR, evError, evRLSD, evRx80Full]
    FlowControl.OutCTSFlow = False
    FlowControl.OutDSRFlow = False
    FlowControl.ControlDTR = dtrDisable
    FlowControl.ControlRTS = rtsDisable
    FlowControl.XonXoffOut = False
    FlowControl.XonXoffIn = False
    StoredProps = [spBasic]
    TriggersOnRxChar = False
    Left = 312
    Top = 80
  end
  object ComDataPacket1: TComDataPacket
    ComPort = ComPort1
    Left = 408
    Top = 80
  end
end
