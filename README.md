# [Soft UI Dashboard PRO Laravel](https://soft-ui-dashboard-pro-laravel.creative-tim.com/login)

![version](https://img.shields.io/badge/version-1.0.0-blue.svg) 
![license](https://img.shields.io/badge/license-MIT-blue.svg)
[![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-soft-ui-dashboard-pro-laravel.svg)](https://github.com/creativetimofficial/ct-soft-ui-dashboard-pro-laravel/issues?q=is%3Aopen+is%3Aissue) 
[![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-soft-ui-dashboard-pro-laravel.svg)](https://github.com/creativetimofficial/ct-soft-ui-dashboard-pro-laravel/issues?q=is%3Aissue+is%3Aclosed)


*Frontend version*: Soft UI Dashboard v1.0.0. More info at https://www.creative-tim.com/product/soft-ui-dashboard-pro

![Image](https://s3.amazonaws.com/creativetim_bucket/products/603/original/soft-ui-dashboard-pro-laravel.jpg)


Soft UI Dashboard PRO Laravel combines hundreds of premium Bootstrap 5 frontend components with an out of the box Laravel backend.

The look & feel is inspired by one of the hottest design trends right now, Soft UI. Add in ready-made Laravel CRUDs and one of the best libraries for building dynamic UIs and you`ve got an awesome starter pack for building web apps.   


## What am I getting?
You're getting a multi-purpose tool for building complex apps.

Soft UI Dashboard PRO Laravel at a glance:
* 300 handcrafted UI components to make your app stand out, based on one of the most popular design trends
* 54 example pages to get you started, including pricing page, project timeline, profile & more  
* 14 customized plug-ins
* Laravel CRUDs for the most used functionalities in any CMS: role-based authentication system, my profile, CRUDs for managing users, roles, items, categories and tags
* Documentation for each component so you can get started fast


## Designed to save time
The backend is fully integrated, meaning you can easily tick all the boxes for a fully-functional admin panel for your custom application. You have hundreds of UI components to choose from, which you can easily edit using Sass files and classes. In short, everything you need so that your app looks like you want it to look and does what you want it to do.


## Free demo
Check out the open-source demo version for a taste of what Soft Ui Dashboard PRO Laravel has to offer. 

## Table of Contents

* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Usage](#usage)
* [Versions](#versions)
* [Demo](#demo)
* [Documentation](#documentation)
* [Login](#login)
* [Register](#register)
* [Forgot Password](#forgot-password)
* [Reset Password](#reset-password)
* [User Profile](#my-profile)
* [User Management](#user-management)
* [Role Management](#role-management)
* [Category Management](#category-management)
* [Tag Management](#tag-management)
* [Item Management](#item-management)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)
* [Social Media](#social-media)
* [Credits](#credits)

## Prerequisites

If you don't already have an Apache local environment with PHP and MySQL, use one of the following links:

 - Windows: https://updivision.com/blog/post/beginner-s-guide-to-setting-up-your-local-development-environment-on-windows
 - Linux: https://howtoubuntu.org/how-to-install-lamp-on-ubuntu
 - Mac: https://wpshout.com/quick-guides/how-to-install-mamp-on-your-mac/

Also, you will need to install Composer: https://getcomposer.org/doc/00-intro.md   
And Laravel: https://laravel.com/docs/9.x/installation


## Installation

1. Unzip the downloaded archive
2. Copy and paste **soft-ui-dashboard-pro-laravel-master** folder in your **projects** folder. Rename the folder to your project's name
3. In your terminal run `composer install`
4. Copy `.env.example` to `.env` and updated the configurations (mainly the database configuration)
5. In your terminal run `php artisan key:generate`
6. Run `php artisan migrate --seed` to create the database tables and seed the roles and users tables
7. Run `php artisan storage:link` to create the storage symlink (if you are using **Vagrant** with **Homestead** for development, remember to ssh into your virtual machine and run the command from there).

## Usage
Register a user or login with the default users with different roles from your database and start testing (make sure to run the migrations and seeders for these credentials to be available):
* **admin@softui.com** and password **secret**
* **creator@softui.com** and password **secret**
* **member@softui.com** and password **secret**

Besides the numerous types of dashboard, you can find pages for editing your profile, pages for managing the users, the roles, the items, the categories and the tags. There are also static pages for profile, for users, for projects, for accounts, for various applications, for ecommerce and different styles of pages for authentication. All the necessary files are installed out of the box and all the needed routes are added to `routes/web.php`. Keep in mind that all of the features can be viewed once you login using the credentials provided or by registering your own user. 

## Versions
[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/html-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/soft-ui-dashboard-pro)
[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/laravel_logo.png?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/soft-ui-dashboard-pro-laravel)

| HTML | Laravel |
| --- | --- |
| [<img src="https://s3.amazonaws.com/creativetim_bucket/products/487/thumb/opt_sdp_thumbnail.jpg" width="483"/>](https://www.creative-tim.com/product/soft-ui-dashboard-pro) | [<img src="https://s3.amazonaws.com/creativetim_bucket/products/603/thumb/soft-ui-dashboard-pro-laravel.jpg" width="483"/>](https://www.creative-tim.com/product/soft-ui-dashboard-pro-laravel)

## Demo
| Register | Login | 
| --- | --- | 
| [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Register.png" width="483" />](https://soft-ui-dashboard-pro-laravel.creative-tim.com/register) | [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Login.png" width="483" />](https://soft-ui-dashboard-pro-laravel.creative-tim.com/login)  

| Forgot Password Page | Reset Password Page | 
| --- | --- | 
| [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Forgot-password.png" width="483" />](https://soft-ui-dashboard-pro-laravel.creative-tim.com/forgot-password) | [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Reset-password.png" width="483" />](https://soft-ui-dashboard-pro-laravel.creative-tim.com) 

| Dashboard | Virtual Reality  |
| ---  | ---  |
| [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Dashboard.png" width="480" />](https://soft-ui-dashboard-pro-laravel.creative-tim.com/dashboard-default) | [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/vr.png" width="484"/>](https://soft-ui-dashboard-pro-laravel.creative-tim.com/dashboard-virtual-reality)

| Profile Page | User Management |
| ---  | ---  |
| [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Profile.png" width="485"/>](https://soft-ui-dashboard-pro-laravel.creative-tim.com/laravel-user-profile) | [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Users-management.png" width="475"/>](https://soft-ui-dashboard-pro-laravel.creative-tim.com/laravel-users-management?q=%2Flaravel-users-management&sortField=id&sortDirection=asc)

| Role Management | Item Management  |
| --- | --- | 
| [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Role-management.png" width="483"/>](https://soft-ui-dashboard-pro-laravel.creative-tim.com/laravel-roles-management?q=%2Flaravel-roles-management&sortField=id&sortDirection=asc)| [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Items-management.png" width="483"/>](https://soft-ui-dashboard-pro-laravel.creative-tim.com/laravel-items-management?q=%2Flaravel-items-management&sortField=id&sortDirection=asc)

| Category Management | Tag Management | 
| --- | --- |
| [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Category-management.png" width="483"/>](https://soft-ui-dashboard-pro-laravel.creative-tim.com/laravel-category-management?q=%2Flaravel-category-management&sortField=id&sortDirection=asc) | [<img src="https://github.com/creativetimofficial/public-assets/blob/master/soft-ui-design-system-pro-laravel/Tags-management.png" width="483"/>](https://soft-ui-dashboard-pro-laravel.creative-tim.com/laravel-tags-management?q=%2Flaravel-tags-management&sortField=id&sortDirection=asc)
[View More](https://soft-ui-dashboard-pro-laravel.creative-tim.com)

## Documentation
The documentation for the Soft UI Dashboard Laravel is hosted at our [website](https://soft-ui-dashboard-pro-laravel.creative-tim.com/documentation/getting-started/overview.html).

### Login
If you are not logged in you can only access this page or the Sign Up page. The default url takes you to the login page where you use the default credentials **admin@softui.com** with the password **secret** but you can change them with the credentials for creator and for member. Logging in is possible only with already existing credentials. For this to work you should have run the migrations. The user also has the option to choose if he wants to be remembered or not.

The `App\Http\Controllers\SessionController` handles the logging in of an existing user.

```
   public function store()
    {
        $attributes = request()->validate([
            'email'=>'required|email',
            'password'=>'required' 
        ]);

        if(Auth::attempt($attributes))
        {
            session()->regenerate();
            return redirect('/');
        }

        return back();
    }
```

### Register
You can register as a user by filling in the name, email, role and password for your account. For your role you can choose between the Admin, Creator and Member. It is important to know that an admin user has access to all the pages and actions, can delete, add and edit another users, other roles, items, tags or categories; a creator user has acces to category, tag and item managemen, but can not add, edit or delete other users; a member user has access to the item management but can not take any action. You can do this by accessing the sign up page from the "**Sign Up**" button in the top navbar or by clicking the "**Sign Up**" button from the bottom of the log in form. Another simple way is adding **/register** in the url.

The `App\Http\Controllers\RegisterController` handles the registration of a new user.

```
    $attributes = request()->validate([
            'role_id' => 'required',
            'name' => ['required', 'max:50'],
            'email' => ['required', 'email', 'max:50', Rule::unique('users', 'email')],
            'password' => ['required', 'min:5', 'max:20'],
            'agreement' => ['accepted']
        ]);
        $insertUser = User::create(
            [
                'role_id' => $attributes['role_id'],
                'first_name' => $attributes['name'],
                'email' => $attributes['email'],
                'password' => $attributes['password'],
            ]
        );
        
        session()->flash('success', 'Your account has been created.');
        Auth::login($insertUser); 
        return view('dashboards/default');
```

### Forgot Password
If a user forgets the account's password it is possible to reset the password. For this the user should click on the "**here**" under the login form or add **/login/forgot-password** in the url.

The `App\Http\Controllers\ChangePasswordController` takes care of sending an email to the user where he can reset the password afterwards.

```
    public function sendEmail(Request $request)
    {
        $request->validate(['email' => 'required|email']);

        $status = Password::sendResetLink(
            $request->only('email')
        );

        return $status === Password::RESET_LINK_SENT
                    ? back()->with(['status' => __($status)])
                    : back()->withErrors(['email' => __($status)]);
    }
```

### Reset Password
The user who forgot the password gets an email on the account's email address. The user can access the reset password page by clicking the button found in the email. The link for resetting the password is available for 12 hours. The user must add the new password and confirm the password for his password to be updated. The user is redirected to the login page.

The `App\Http\Controllers\ChangePasswordController` helps the user reset the password.

```
    public function changePassword(Request $request)
    {
        
        $request->validate([
            'token' => 'required',
            'email' => 'required|email',
            'password' => 'required|min:8|confirmed',
        ]);
    
        $status = Password::reset(
            $request->only('email', 'password', 'password_confirmation', 'token'),
            function ($user, $password) {
                $user->forceFill([
                    'password' => Hash::make($password)
                ])->setRememberToken(Str::random(60));
    
                $user->save();
    
                event(new PasswordReset($user));
            }
        );
    
        return $status === Password::PASSWORD_RESET
                    ? redirect('/login')->with('status', __($status))
                    : back()->withErrors(['email' => [__($status)]]);
    }
```

### My Profile
The profile can be accessed by a logged in user by clicking "**User Profile**" from the sidebar or adding **/laravel-user-profile** in the url. The user can add information like birthday, gender, phone number, location, language  or skills.

The `App\Http\Controllers\UserProfileController` handles the user's profile information.

```
    public function store(Request $request)
    {

        if($request->get('choices-year') || $request->get('choices-month') || $request->get('choices-day'))
        {
            $birthday = $request->get('choices-year').'-'.$request->get('choices-month').'-'.$request->get('choices-day');
        }
        else{
            $birthday = Null;
        }

        if(!empty($request->file('user_img'))) {
            $uniqueFileName = uniqid().$request->file('user_img')->getClientOriginalName();
            $request->file('user_img')->move(public_path('/assets/img/users/'),$uniqueFileName);
        }
        else{
            $uniqueFileName = auth()->user()->file;
        }
        
        User::where('id','=',auth()->user()->id)
            ->update([
                'first_name'    => $request->get('firstName'),
                'file' => $uniqueFileName,
                'last_name'    => $request->get('lastName'),
                'gender'    => $request->get('choices-gender'),
                'birthday'    => $birthday,
                'email'    => $request->get('email'),
                'Address_1'    => $request->get('location'),
                'phone'     => $request->get('phone'),
                'language'    => $request->get('choices-language'),
                'skills' => $request->get('skills'),
            ]);
        return redirect('/laravel-user-profile');
    }
```

### User Management
The user management can be accessed by clicking "**User Managmenet**" from the **Laravel Examples** section from the sidebar or by adding "**/laravel-users-management** in the url. This page is available for users with the **Admin** role and the user is able to **add**, **edit** and **delete** other users. For adding a new user you can press the "**+ New User**" button or add in the url "**/laravel-new-user**". If you would like to edit or delete an user you can click on the **Action** column. It is also possible to sort the fields or to search in the fields.

On the page for adding a new user you will find a form which allows you to fill the information. All pages are generated using blade templates.

In `/resources/views/laravel-examples/users/users-management.blade.php`: 
```
    @if(count($users) > 1)
        @foreach($users as $user)
            <tr>
            <td class="text-sm">{{$user->id}}</td>
            <td class="text-sm">
                <span class="my-2 text-xs">
                <img src="{{ URL::asset('assets/img/users/'.$user->file) }}" alt="picture" class="avatar avatar-xxl me-2">
                </span>
            </td>
            <td class="text-sm">{{$user->first_name}}</td>
            <td class="text-sm">{{$user->email}}</td>
            <td class="text-sm">{{$user->roles->name}}</td>
            <td class="text-sm">{{$user->created_at}}</td>
            <td class="text-sm">
                <a href="{{ url('laravel-edit-users/' . $user->id) }}" class="mx-3" data-bs-toggle="tooltip" data-bs-original-title="Edit user">
                <i class="fas fa-user-edit text-secondary"></i>
                </a>
                @if ($user->id < 4)
                <span" data-bs-toggle="tooltip" data-bs-original-title="Disabled" data-bs-original-title="Delete user">
                <i class="fas fa-trash text-secondary"></i>
                </span>
                @else
                <a href="{{ url('laravel-delete-user/' . $user->id) }}" data-bs-toggle="tooltip" data-bs-original-title="Delete user">
                <i class="fas fa-trash text-secondary"></i>
                </a>
                @endif
            </td>
            </tr>
        @endforeach
    @endif
```

The `App\Http\Controllers\UsersController` takes care of data validation and creating the new user:

```
    public function validateOne(Request $request)
    {
        $validatedData = $request->validate([
            'first_name' => ['required', 'max:50'],
            'last_name' => ['max:50'],
            'role_id' => ['required'],
            'company' => ['max:150'],
            'email' => ['required', 'email', 'max:50', Rule::unique('users', 'email')],
            'password' => ['required', 'min:5', 'max:20', 'confirmed'],
        ]);
  
        if(empty($request->session()->get('user'))){
            $user = new User();
            $user->fill($validatedData);
            $request->session()->put('user', $user);
        }else{
            $user = $request->session()->get('user');
            $user->fill($validatedData);
            $request->session()->put('user', $user);
        }
  
        return redirect()->route('users.create.step.two');
    }
```
Once the user pressed **Send** at the end of the form the new user is added to the table.
For authorizing this actions have been used policies such as `App\Policies\UserPolicy`:
```
    /**
     * Determine whether the authenticate user can manage other users.
     *
     * @param  \App\User  $user
     * @return boolean
     */
    public function manageUsers(User $user)
    {
        return $user->isAdmin();
    }
```

### Role Management
The PRO version lets you add roles to the user. The default roles are **Admin**, **Creator**  and **Member**. The role management can be accessed by clicking "**Role Managmenet**" from the **Laravel Examples** section of the sidebar or by adding "**/laravel-roles-management** in the url. This page is available for users with the **Admin** role and the user is able to **add**, **edit** and **delete** roles. For adding a new role you can press the "**+ New Role**" button or add in the url "**/laravel-new-role**". If you would like to edit or delete a role you can click on the **Action** column. It is also possible to sort the fields or to search in the fields.

On the page for adding a new role you will find a form which allows you to fill the name and the description of the new role.

The `App\Http\Controllers\RolesController` takes care of data validation and creation of a the new role:

```
    public function store()
    {
        $attributes = request()->validate([
            'name' => ['required'],
            'description' => ['required'],
        ]);  
        DB::table('roles')
            ->insert(['name' => $attributes['name'], 'description'=> $attributes['description'], 'created_at' => now(), 'updated_at' => now()]);
        return redirect('/laravel-roles-management');
    }
```

### Category Management
The theme has some default categories but an **Admin** or **Creator** user can manage these categories.The category management can be accessed by clicking "**Category Management**" from the **Laravel Examples** section of the sidebar or by adding "**/laravel-category-management** in the url. The authenticated user can **add**, **edit** and **delete** categories. For adding a new category you can press the "**+ New Category**" button or add in the url "**/laravel-new-category**". If you would like to edit or delete a category you can click on the **Action** column. It is also possible to sort the fields or to search in the fields.

On the page for adding a new category you will find a form which allows you to fill the name and the description of the new category.

The `App\Http\Controllers\CategoryController` takes care of data validation when changing a category and updating it:

```
    public function store(Request $request)
    {
        $attributes = request()->validate([
            'name' => ['required'],
            'description' => ['required'],
        ]); 
        DB::table('category')
            ->insert(['name' => $attributes['name'], 'description'=> $attributes['description'], 'created_at' => now(), 'updated_at' => now()]);
        return redirect('/laravel-category-management');
    }
```

### Tag Management
The theme has some default tags but an **Admin** or **Creator** user can manage these tags.The tag management can be accessed by clicking "**Tag Managmenet**" from the **Laravel Examples** section from the sidebar or by adding "**/laravel-tags-management** in the url. The authenticated user can **add**, **edit** and **delete** tags. For adding a new tag you can press the "**+ New Tag**" button or add in the url "**/laravel-new-tag**". If you would like to edit or delete a tag you can click on the **Action** column. It is also possible to sort the fields or to search in the fields.

On the page for adding a new category you will find a form which allows you to fill the name and the description of the new tag and on the edit page you will find a similar form for the changes you wish to make.

The `/resources/views/livewire/laravel-examples/edit-tag.blade.php` is the blade template for editing a tag:

```
    <div>
        <label class="mt-4">{{ __('Tag Description') }}</label>
        <div class="@error('tag.color') has-danger @enderror">
            <input wire:model="tag.color" type="color" name="color" id="input-name"
                    class="form-control @error('tag.color') is-invalid @enderror" placeholder="Color"
                    value="{{ old('color') }}" required>
        </div>
        @error('tag.color') <div class="text-danger text-xs">{{ $message }}</div>@enderror
    </div>
```

### Item Management
Item Management is the most advanced example included in the PRO theme because every item has a picture, has a category and has multiple tags. The item management can be accessed by clicking "**Item Managmenet**" from the **Laravel Examples** section of the sidebar or by adding "**/laravel-items-management** in the url. The authenticated user as an Admin or Creator can **add**, **edit** and **delete** items. For adding a new item you can press the "**+ New Item**" button or add in the url "**/laravel-new-item**". If you would like to edit or delete an item you can click on the **Action** column. It is also possible to sort the fields or to search in the fields. The Member user can not take any actions on the item, he is only able to see the item management table.

On the page for adding a new item you will find a form which allows you to add an image of the item, to  fill the name, excerpt, description of the item, a dropdown to choose the category and a multiselect for the tags.

The `App\Http\Controllers\ItemsController` takes care of data validation when adding a new item and of the item creation(see snippet below):

```
    public function store(Request $request)
    {
        if(!empty($request->file('item_img'))) {
            $uniqueFileName = uniqid().$request->file('item_img')->getClientOriginalName();
            $request->file('item_img')->move(public_path('/assets/img/items/'),$uniqueFileName);
        }
        else{
            $uniqueFileName = 'default/default.jpg';
        }

        $attributes = request()->validate([
            'name' => ['required', 'max:50'],
            'excerpt' => ['max:150'],
            'category_id' => ['required'],
            'tag_id' => ['required'],
            'description' => ['max:200'],
        ]); 
        $request->all();
        
        $optionList = $request->input('option');
        $tags = $request->input('tag_id');

        $items = new Item();
            $items->name = $attributes['name'];
            $items->file = $uniqueFileName;
            $items->excerpt = $attributes['excerpt'];
            $items->description = $request->get('description');
            $items->category_id = $attributes['category_id'];
            $items->status = $request->get('status');
            $items->show_homepage = $request->get('show_homepage');
            $items->options = $request->get('option');
            $items->date = $request->get('date');
            $items->created_at = now();
            $items->updated_at = now();
            $items->options = json_encode($optionList);
            $items->save();
            
            $items->tags()->attach($tags);
            return redirect('/laravel-items-management');
    }
```
For deleting an item is necessary to remove the association between item and tags. The `App\Http\Controllers\ItemsController` handles the deletion of an item:
```
    public function destroy($id)
    {
        try{
            DB::table('items_management')->where('id','=', $id)->delete();
            return redirect('/laravel-items-management')
                ->with('success','Item deleted successfully');
                }catch(Exception $e){
                //if email or phone exist before in db redirect with error messages
                    return redirect()->back()->withErrors(['msgError' => 'You can\'t delete this item.']);
                }
    }
```

## File Structure
```
app
├── Console
│   └── Kernel.php
├── Exceptions
│   └── Handler.php
├── Http
│   ├── Controllers
│   │   └── CategoryController.php
│   │   └── ChangePasswordController.php
│   │   └──Controller.php
│   │   └──ItemsController.php
│   │   └──RegisterController.php
│   │   └──RolesController.php
│   │   └──SessionController.php
│   │   └──TagsController.php
│   │   └──UserProfileController.php
│   │   └──UsersController.php
│   ├── Kernel.php
│   └── Middleware
│       ├── Authenticate.php
│       ├── EncryptCookies.php
│       ├── PreventRequestsDuringMaintenance.php
│       ├── RedirectIfAuthenticated.php
│       ├── TrimStrings.php
│       ├── TrustHosts.php
│       ├── TrustProxies.php
│       └── VerifyCsrfToken.php
├── Models
│   ├── Category.php
│   ├── Item.php
│   ├── Role.php
│   ├── Tag.php
│   └── User.php
├── Policies
│   └── UsersPolicy.php
├── Providers
│   ├── AppServiceProvider.php
│   ├── AuthServiceProvider.php
│   ├── BroadcastServiceProvider.php
│   ├── EventServiceProvider.php
│   └── RouteServiceProvider.php
config
├── app.php
├── auth.php
├── broadcasting.php
├── cache.php
├── cors.php
├── database.php
├── filesystems.php
├── hashing.php
├── logging.php
├── mail.php
├── queue.php
├── sanctum.php
├── services.php
├── session.php
├── view.php
|       
database
|   ├──factories
|   |       UserFactory.php
|   |       
|   ├──migrations
|   |       2013_11_25_113948_create_roles_table.php
|   |       2014_10_12_000000_create_users_table.php
|   |       2014_10_12_100000_create_password_resets_table.php
|   |       2019_08_19_000000_create_failed_jobs_table.php
|   |       2019_12_14_000001_create_personal_access_tokens_table.php
|   |       2021_11_25_114000_create_tags_table.php
|   |       2021_11_25_114007_create_category_table.php
|   |       2021_11_25_114219_create_items_management_table.php
|   |       2021_12_06_091622_create_item-tags_table.php
|   |       
|   └──seeds
|           CategorySeeder.php
|           DatabaseSeeder.php
|           ItemsManagementSeeder.php
|           ItemTagsSeeder.php
|           RoleSeeder.php
|           TagsSeeder.php
|           UserTableSeeder.php
|           
+---public
|   |   .htaccess
|   |   favicon.ico
|   |   index.php
|   |   
|   +---css
|   |       app.css
|   |       soft-ui-dashboard.css
|   +---js
|   |       app.js
|   |       
|   +---assets
|   |       demo.css
|   |       docs-soft.css
|   |       docs.js
|   |
|   |   +---css
|   |   |   |   nucleo-icons.css
|   |   |   |   nucleo-svg.css
|   |   |   |   soft-ui-dashboard.css
|   |   |   |   soft-ui-dashboard.css.map
|   |   |   └── soft-ui-dashboard.min.css
|   |   |                                 
|   +---+---js
|           |   soft-ui--dashboard.js
|           |   soft-ui--dashboard.js.map
|           |   soft-ui--dashboard.min.js
|           |   
|           +---core
|                   bootstrap.bundle.min.js
|                   bootstrap.min.js
|                   popper.min.js
|                    
+---resources
|   +---lang
|   |   \---en
|   |           auth.php
|   |           pagination.php
|   |           passwords.php
|   |           validation.php
|   |           
|   \---views
|       |   app.blade.php
|       |   
|       +---applications
|       |       analytics.blade.php
|       |       calendar.blade.php
|       |       datatables.blade.php
|       |       kanban.blade.php
|       |       wizard.blade.php
|       |       
|       +---authentification
|       |   +---error
|       |   |      404.blade.php
|       |   |      500.blade.php
|       |   |      
|       |   +---lock
|       |   |      basic.blade.php
|       |   |      cover.blade.php
|       |   |      illustration.blade.php
|       |   |       
|       |   +---reset
|       |   |      basic.blade.php
|       |   |      cover.blade.php
|       |   |      illustration.blade.php
|       |   |      
|       |   +---signin
|       |   |      basic.blade.php
|       |   |      cover.blade.php
|       |   |      illustration.blade.php
|       |   |      
|       |   +---signup
|       |   |      basic.blade.php
|       |   |      cover.blade.php
|       |   |      illustration.blade.php
|       |   |      
|       |   +---verification
|       |          basic.blade.php
|       |          cover.blade.php
|       |          illustration.blade.php
|       |                 
|       +---components
|       |       fixed-plugins.blade.php
|       |       
|       +---dashboard
|       |    +---vr
|       |    |    vr-default.blade.php
|       |    |    vr-info.blade.php
|       |    |  automative.blade.php
|       |    |  crm.blade.php
|       |    |  default.blade.php
|       |    +--smart-home.blade.php
|       |       
|       +---ecommerce
|       |       +---orders
|       |       |      details.blade.php
|       |       |      list.blade.php
|       |       +---products
|       |       |      edit-product.blade.php
|       |       |      new-product.blade.php
|       |       |      product-page.blade.php
|       |       |      product-list.blade.php
|       |       overview.blade.php
|       |       referral.blade.php
|       |  
|       +---laravel-example
|       |       |
|       |       +---category
|       |       |      add-category.blade.php
|       |       |      category-management.blade.php
|       |       |      edit-category.blade.php
|       |       |
|       |       +---items
|       |       |      add-items.blade.php
|       |       |      edit-items.blade.php
|       |       |      items-management.blade.php
|       |       |
|       |       +---roles
|       |       |      add-roles.blade.php
|       |       |      edit-roles.blade.php
|       |       |      roles-management.blade.php
|       |       |
|       |       +---tags
|       |       |      add-tags.blade.php
|       |       |      edit-tags.blade.php
|       |       |      tags-management.blade.php
|       |       |
|       |       +---users
|       |       |      add-step-one.blade.php
|       |       |      add-step-two.blade.php
|       |       |      add-step-three.blade.php
|       |       |      add-step-four.blade.php
|       |       |      edit-step-one.blade.php
|       |       |      edit-step-two.blade.php
|       |       |      edit-step-three.blade.php
|       |       |      edit-step-four.blade.php
|       |       |      users-management.blade.php
|       |       |
|       |       user-profile.blade.php
|       |      
|       +---layouts
|       |   |   
|       |   +---footers
|       |   |   |
|       |   |   +--auth
|       |   |   |     footer.blade.php
|       |   |   +--guest
|       |   |         footer.blade.php
|       |   |
|       |   +---navbars
|       |       |
|       |       +--auth
|       |       |     nav-auth-basic.blade.php
|       |       |     nav-auth-cover.blade.php
|       |       |     nav-rtl.blade.php
|       |       |     nav.blade.php
|       |       |     sidebar.blade.php
|       |       +--guest
|       |             nav.blade.php
|       |           
|       +---pages
|       |   |   charts.blade.php
|       |   |   notifications.blade.php
|       |   |   pricing-page.blade.php
|       |   |   rtl-page.blade.php
|       |   |   sweet-alerts.blade.php
|       |   |   widgets.blade.php
|       |   |   
|       |   +---account
|       |   |       billing.blade.php
|       |   |       invoice.blade.php
|       |   |       security.blade.php
|       |   |       setting.blade.php
|       |   |       
|       |   +---profile
|       |   |       overview.blade.php
|       |   |       projects.blade.php
|       |   |       teams.blade.php
|       |   |       
|       |   +---projects
|       |   |       general.blade.php
|       |   |       new-project.blade.php
|       |   |       timeline.blade.php
|       |   |       
|       |   +---users
|       |           new-user.blade.php
|       |           reports.blade.php
|       |           
|       +---session
|       |   |   login.blade.php
|       |   |   register.blade.php
|       |   |   
|       |   +---reset-password
|       |           resetPassword.blade.php
|       |           sendEmail.blade.php
|       |       
|       +---user-type
|               auth.blade.php
|               guest.blade.php
|                      
+---routes
|       api.php
|       channels.php
|       console.php
|       web.php
```

## Browser Support
At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Reporting Issues
We use GitHub Issues as the official bug tracker for the Soft UI Dashboard. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Soft UI Dashboard. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/product/soft-ui-dashboard-pro-laravel?ref=readme-sudpl).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Licensing
- Copyright 2021 [Creative Tim](https://www.creative-tim.com?ref=readme-sudpl)
- Creative Tim [license](https://www.creative-tim.com/license?ref=readme-sudpl)

## Useful Links
- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)
- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)
- [Blog Creative Tim](http://blog.creative-tim.com/)
- [Free Products](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim
- [Premium Products](https://www.creative-tim.com/bootstrap-themes/premium?ref=sudpl-readme) from Creative Tim
- [React Products](https://www.creative-tim.com/bootstrap-themes/react-themes?ref=sudpl-readme) from Creative Tim
- [VueJS Products](https://www.creative-tim.com/bootstrap-themes/vuejs-themes?ref=sudpl-readme) from Creative Tim
- [More products](https://www.creative-tim.com/bootstrap-themes?ref=sudpl-readme) from Creative Tim
- Check our Bundles [here](https://www.creative-tim.com/bundles??ref=sudpl-readme)

### Social Media

### Creative Tim
Twitter: <https://twitter.com/CreativeTim?ref=sudpl-readme>

Facebook: <https://www.facebook.com/CreativeTim?ref=sudpl-readme>

Dribbble: <https://dribbble.com/creativetim?ref=sudpl-readme>

Instagram: <https://www.instagram.com/CreativeTimOfficial?ref=sudpl-readme>

### Updivision:

Twitter: <https://twitter.com/updivision?ref=sudpl-readme>

Facebook: <https://www.facebook.com/updivision?ref=sudpl-readme>

Linkedin: <https://www.linkedin.com/company/updivision?ref=sudpl-readme>

Updivision Blog: <https://updivision.com/blog/?ref=sudpl-readme>

## Credits

- [Creative Tim](https://creative-tim.com/?ref=sudl-readme)
- [UPDIVISION](https://updivision.com)
