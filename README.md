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





<Window x:Class="Wprowadzenie.Window2"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:Wprowadzenie"
        mc:Ignorable="d"
        Title="Window2" Height="450" Width="800">
    <Grid>
        <Grid.ColumnDefinitions>
            <ColumnDefinition Width="auto"></ColumnDefinition>
            <!--
            szerokosc taka jak zawartosc
            -->
            <ColumnDefinition Width="*"></ColumnDefinition>
            <ColumnDefinition Width="3*"></ColumnDefinition>
            <ColumnDefinition></ColumnDefinition>
        </Grid.ColumnDefinitions>
        <Grid.RowDefinitions>
            <RowDefinition Height="*"></RowDefinition>
            <RowDefinition Height="2*"></RowDefinition>
            <RowDefinition Height="3*"></RowDefinition>
        </Grid.RowDefinitions>
        <Button>1</Button>
        <!--
        domyslnie w kolumnie 0 i wierszu 0
        -->
        <Button Grid.Column="2" Grid.Row="1">2</Button>
        <Button Grid.Row="2" Grid.ColumnSpan="2" Margin="30">3</Button>
        <Button Grid.Column="3" Grid.RowSpan="3" Margin="20">4</Button>
    </Grid>
</Window>

