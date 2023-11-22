<Window x:Class="Wprowadzenie.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:Wprowadzenie"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <StackPanel>
        <!---
        uklad liniowy
        domyslnie elementy jeden pod drugim
        -->
        <Button>1</Button>
        <Button>2</Button>
        <Button>3</Button>
        <Button>4</Button>
        <Button>5</Button>
        <StackPanel Orientation="Horizontal">
            <!--
            tu zmienione na jeden obok drugiego
            -->
            <Button>1111</Button>
            <Button>2</Button>
            <Button>3</Button>
            <Button>4</Button>
            <Button>5</Button>
        </StackPanel>
    </StackPanel>
    
</Window>







<Window x:Class="Wprowadzenie.Window1"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:Wprowadzenie"
        mc:Ignorable="d"
        Title="Window1" Height="450" Width="800">
    <UniformGrid Columns="3">
        <!--
        uklad siatki
        -->
        <Button Background="Azure">1</Button>
        <Button Foreground="Bisque">2</Button>
        <Button>3</Button>
        <Button Foreground="Red">4</Button>
        <Button>5</Button>
        <Button Margin="20">5</Button>
        <Button>5</Button>
        <Button Padding="30">5</Button>
        <Button>5</Button>
        <Button>5</Button>
        <Button>5</Button>

        <UniformGrid Rows="2">
            <Button>1</Button>
            <Button>2</Button>
            <Button>3</Button>
            <Button>4</Button>
            <Button>5</Button>
            <Button>5</Button>
            <Button>5</Button>
            <Button>5</Button>
            <Button>5</Button>
            <Button>5</Button>
            <Button>5</Button>
        </UniformGrid>
    </UniformGrid>
</Window>
