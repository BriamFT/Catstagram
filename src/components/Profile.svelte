<script>
  export let nickname;
  export let name;
</script>

<div class="Profile">
    <div class="profile-content">
        <div class="profile-avatar">
            <img src="https://icon-library.com/images/avatar-icon-images/avatar-icon-images-4.jpg" alt=""/>
        </div>
    </div>
    <div class="profile-info">
        <h2>{nickname}</h2>
        <span>{name}</span>
    </div>
</div>

<style>
    .profile-content {
      display: flex;
      align-items: center;
    }
    .profile-avatar img {
      width: 42px;
      height: 42px;
      border-radius: 50%;
    }
    .profile-info {
      margin: 0 0 0 0.5em;
    }
    .profile-info h2 {
      font-size: 14px;
      color: black;
      margin: 0;
      padding: 0;
    }
    .profile-info span {
      font-size: 12px;
      font-weight: normal;
    }
</style>
  