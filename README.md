# Android1
Primer proyecto Andoid semana 3
Espero estasr agregando el proyecto de la manera correcta 

activity_main.xml


<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.begin.ely.marcianito.MainActivity">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="363dp"
        android:layout_height="527dp"
        android:layout_marginTop="-8dp"
        android:scaleType="centerCrop"
        android:src="@drawable/marcianito1"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/marcianito1"
        android:layout_marginRight="-2dp" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:text="TextView"
        android:textAppearance="@android:style/TextAppearance.WindowTitle"
        android:textSize="?android:attr/windowTitleSize"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        tools:text="@string/titulo"
        app:layout_constraintTop_toTopOf="@+id/imageView"
        android:layout_marginTop="8dp"
        app:layout_constraintHorizontal_bias="0.507"
        app:layout_constraintBottom_toBottomOf="parent"
        android:layout_marginBottom="8dp"
        app:layout_constraintVertical_bias="0.132" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginTop="8dp"
        android:background="?android:attr/colorBackgroundCacheHint"
        android:text="@string/Btn2"
        android:visibility="visible"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2"
        app:layout_constraintVertical_bias="0.061" />
</android.support.constraint.ConstraintLayout>



activity_main.xml land



<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.begin.ely.marcianito.MainActivity">

    <ImageView
        android:id="@+id/imageView3"
        android:layout_width="612dp"
        android:layout_height="301dp"
        android:layout_marginLeft="8dp"
        android:layout_marginTop="0dp"
        android:scaleType="centerCrop"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/marcianito1"
        android:layout_marginRight="0dp"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintHorizontal_bias="0.642"
        app:layout_constraintBottom_toBottomOf="parent"
        android:layout_marginBottom="0dp"
        app:layout_constraintVertical_bias="1.0" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="TextView"
        android:textAppearance="@android:style/TextAppearance.WindowTitle"
        android:textSize="?android:attr/windowTitleSize"
        tools:text="@string/titulo"
        android:layout_marginLeft="8dp"
        app:layout_constraintLeft_toLeftOf="parent"
        android:layout_marginRight="8dp"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        android:layout_marginTop="8dp"
        app:layout_constraintHorizontal_bias="0.501"
        app:layout_constraintBottom_toBottomOf="@+id/imageView3"
        android:layout_marginBottom="8dp"
        app:layout_constraintVertical_bias="0.037" />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="149dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginTop="8dp"
        android:background="?android:attr/colorBackgroundCacheHint"
        android:text="Button"
        android:textColor="@android:color/background_light"
        app:layout_constraintBottom_toBottomOf="@+id/imageView3"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView"
        app:layout_constraintVertical_bias="0.2"
        tools:text="@string/Btn2" />
</android.support.constraint.ConstraintLayout>



activity_main.xml xlarge



<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.begin.ely.marcianito.MainActivity">

    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="1198dp"
        android:layout_height="989dp"
        android:layout_marginTop="0dp"
        android:scaleType="centerCrop"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/marcianito1"
        android:layout_marginLeft="0dp"
        app:layout_constraintLeft_toLeftOf="parent"
        android:layout_marginRight="0dp"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintBottom_toBottomOf="parent"
        android:layout_marginBottom="0dp"
        app:layout_constraintVertical_bias="0.714"
        app:layout_constraintHorizontal_bias="0.613"
        android:contentDescription="marcianito1" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginTop="8dp"
        android:text="@string/titulo"
        android:textColor="@android:color/background_light"
        android:textSize="?android:attr/windowTitleSize"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.134"
        tools:text="@string/titulo" />

    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginTop="8dp"
        android:background="?android:attr/colorBackgroundCacheHint"
        android:text="@string/Btn2"
        android:textColor="@android:color/background_light"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView"
        app:layout_constraintVertical_bias="0.063" />
</android.support.constraint.ConstraintLayout>


strings.xml


<resources>
    <string name="app_name">Marcianito</string>
    <string name="titulo">Bienvenido</string>
    <string name="Btn2">Entrar</string>
</resources>

strings.xml de

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name">Marcianitofra</string>
    <string name="titulo">Willkommen</string>
    <string name="Btn2">Eintreten</string>
</resources>


strings.xml en

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name">MarcianitoEn</string>
    <string name="titulo">Welcome</string>
    <string name="Btn2">Enter</string>
</resources>

strings.xml fr

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="app_name">Marcianitofra</string>
    <string name="titulo">Bienvenue</string>
    <string name="Btn2">pour entrer</string>
</resources>
